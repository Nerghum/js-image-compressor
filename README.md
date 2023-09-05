
# Image Compressor Web Application

The Image Compressor Web Application allows users to upload multiple image files, compress them, and download the compressed images. This documentation provides instructions on how to use the application and how to customize the image compression settings.

## Features

- Upload multiple image files at once.
- Compress the uploaded images.
- Download the compressed images with customizable filenames.

## Usage

1. Open the web application by opening the HTML file in your web browser.

2. Click the "Choose Files" or "Browse" button to select one or more image files from your computer. You can select multiple images at once.

3. Once you've selected the image files, the application will display the original images along with their compressed versions and download links.

4. The compressed images are generated with a default quality level of 0.7. You can customize the quality level in the JavaScript code if needed.

5. To download a compressed image, click the "Download" button associated with that image.

6. The downloaded image will have a filename like "compressed_image_1.jpg," where "1" represents the order of the image in the list. You can customize the filename format in the JavaScript code.

## Customization

If you want to customize the image compression settings or the filename format for downloaded images, you can do so by modifying the JavaScript code in the HTML file.

- Open the HTML file in a text editor.

- Locate the JavaScript code block inside the `<script>` tag.

- You can change the quality level by modifying the `canvas.toDataURL("image/jpeg", 0.7)` line. Adjust the quality value (e.g., change `0.7` to `0.5`) to increase or decrease the compression quality.

- You can customize the filename format by modifying the `downloadLink.download` attribute. By default, it uses the format "compressed_image_X.jpg," where "X" represents the image's order. You can change the filename to match your preferences.

- Save the HTML file after making changes.

- Refresh the web application in your browser to see the updated behavior.

## Support

If you encounter any issues with the Image Compressor Web Application or have any questions, please feel free to contact us at [nerghum@gmail.com](mailto:nerghum@gmail.com).

## Credits

This web application is provided by Nerghum(https://www.nerghum.com).

Enjoy using the Image Compressor Web Application!
