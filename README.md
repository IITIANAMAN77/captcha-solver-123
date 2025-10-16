# Captcha Solver Application

This project provides a simple, single-file responsive HTML application designed to act as a basic Captcha solver interface. It displays an image, allows the user to input text, and provides feedback. The application uses Tailwind CSS for styling and includes basic JavaScript for handling image loading from URL parameters and verifying the captcha for a default image.

## Features

-   **Responsive Design**: Built with Tailwind CSS, ensuring a consistent experience across various devices.
-   **Dynamic Image Loading**: Supports loading captcha images via a URL query parameter (`?url=https://.../image.png`).
-   **Default Captcha Image**: Defaults to `sample.png` if no URL parameter is provided.
-   **Basic Captcha Verification**: For the default `sample.png` image, it checks if the user's input matches the known answer "ADCRB".
-   **User Feedback**: Provides immediate feedback (Correct/Incorrect/Submission Received) to the user.

## Usage

1.  **Open `index.html` in your browser.**
2.  **Default Image**: By default, the application will display `sample.png`.
    -   Enter `ADCRB` into the input field and click "Submit" to see a "Correct!" message.
3.  **Custom Image**: To load a custom captcha image, append a `?url=` query parameter to the URL in your browser's address bar.
    -   Example: `file:///path/to/index.html?url=https://example.com/some-other-captcha.png`
    -   When a custom URL is used, the application will display a "Submission received. For dynamic URLs, manual verification is expected." message, as it does not have the intelligence to solve arbitrary captchas.

## Installation

This is a single-file application. No complex installation steps are required.

1.  Save the `index.html` file.
2.  Ensure `sample.png` is in the same directory as `index.html` if you intend to use the default image.
3.  Open `index.html` directly in any modern web browser.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
