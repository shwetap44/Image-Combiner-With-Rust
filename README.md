# Image-Combiner-With-Rust

- This Project accepts 2 files to be combined pixel to pixel. It accepts file path in cmd
- It'll throw an error if the formats are not matching
- It gets the smallest dimension between the 2 images and sets the height and width of the output image
- It combines the images using the alternate pixels from both input images
- combined output is saved to an output image
- All the possible errors are handled using enum ImageDataErrors

- To run this prject run the cmd - cargo run -- images/crown.jpeg images/download.jpeg images/output.jpeg 
