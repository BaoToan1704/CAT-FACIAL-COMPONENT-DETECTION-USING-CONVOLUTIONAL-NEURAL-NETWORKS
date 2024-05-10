# CAT FACIAL COMPONENT DETECTION USING CONVOLUTIONAL NEURAL NETWORKS

![Main application](https://ibb.co/9yS5fyN)

This application allows users to upload images of cats and apply various fun filters to them, such as adding glasses or other entertaining effects. It is built using a combination of modern web technologies and computer vision techniques.

The front-end of the application is developed using HTML, CSS, and JavaScript, providing a user-friendly interface for image upload and filter selection. The back-end is powered by Python and the Flask web framework, handling the image processing and filter application logic.

The core functionality of the application relies on computer vision techniques implemented using the OpenCV library and MobileNetV2 tensorflow model. This library is used for accurate detection and localization of cat faces within the uploaded images, enabling precise application of the chosen filters.

The application follows best practices for web development, including responsive design principles to ensure a seamless experience across different devices and screen sizes. Additionally, it incorporates error handling and input validation mechanisms to enhance user experience and application stability.

With its fun and interactive features, this web application is sure to delight cat lovers and provide an engaging way to personalize and enhance their favorite feline photos.
## Getting Started
To get started with the application, follow these steps:
1. Unzip the project file to a directory of your choice.
2. Open a terminal or command prompt and navigate to the project directory.
3. Install the required dependencies by running the following command:
```sh
pip install -r requirements.txt
```
4. Once the dependencies are installed, run the util.py file to set up the application for the first time:
```sh
python util.py
```
5. After running util.py, start the server by running the following command:
```sh
python server.py
```
The server should now be running, and you can interact with the application through the user interface.
## Using the Application

1. Open your web browser and navigate to the URL provided by the server (e.g., http://localhost:5000).
2. On the application's web page, you will see an option to upload an image of a cat.
3. Click the "Upload Image" button and select an image file from your computer.
4. Once the image is uploaded, you will see various filter options below the image.
5. Choose the desired filter option by clicking on the desired glasses image button.
6. The filtered image will be displayed on the web page.
7. You can repeat steps 3-6 to apply additional filters or upload a new image.

Note: If you encounter any issues or have questions, please refer to the documentation or contact the development team for assistance.

## Contributing
Contributions are welcome! Feel free to open an issue or PR for any bugs or desired new features.
## License
This project is licensed under the MIT License. See the LICENSE.txt file for more details.
## Contact
For any questions or feedback, please contact:
baotoantrinh2002@gmail.com.
nguyenduytuan2@gmail.com


