# Gaussian Blur with Adjustable Parameters

This project applies a **Gaussian blur** to an uploaded image using JavaScript. Users can adjust the blur radius and sigma to control the intensity of the effect. The project generates a **Pascal Gaussian Kernel** dynamically for the blurring process.

## Key Features
- **Image Upload**: Users can upload images to apply the Gaussian blur.
- **Adjustable Parameters**: 
  - **Radius**: Determines the size of the blur area.
  - **Sigma**: Controls the spread of the Gaussian function.
- **Dynamic Kernel Generation**: The `createPascalGaussianKernel` function generates a Pascal kernel based on the provided radius and sigma values.

## How It Works
1. **Input**: Users upload an image.
2. **Parameter Adjustment**: Modify the radius and sigma values to customize the blur.
3. **Kernel Creation**: The `createPascalGaussianKernel` function generates the Gaussian kernel dynamically.
4. **Output**: The blurred image is displayed for comparison with the original.

## Technologies Used
- **JavaScript**: Implements the Gaussian blur algorithm.
- **Canvas API**: For rendering and manipulating the image data.

## How to Use
- Clone the repository:
   ```bash
   git clone https://github.com/your-username/gaussian-blur-js.git
- Open index.html in a browser.
- Upload an image using the upload button.
- Adjust the radius and sigma sliders to customize the blur.
- View the blurred image alongside the original.
## Future Improvements
- Add support for real-time adjustments with a live preview.
- Compare Gaussian blur with other smoothing methods (e.g., bilateral or median filters).
- Allow users to save the blurred image locally.
## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.
