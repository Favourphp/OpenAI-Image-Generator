# OpenAI Image Generator

The OpenAI Image Generator is a Node.js application built using Express.js and MongoDB that utilizes the OpenAI API to generate random images. This project demonstrates the integration of OpenAI's powerful image generation capabilities into a web application.

## Prerequisites

To run this application, you need to have the following software installed on your machine:

- Node.js (version 12 or above)
- Express
- OpenAi

## Installation

1. Clone the repository:
git clone https://github.com/favourphp/openai-image-generator.git

2. Navigate to the project directory:

cd openai-image-generator
 Install the dependencies:

npm install
Create a `.env` file in the root directory of the project and provide the following configurations:

OPENAI_API_KEY=<your_openai_api_key>


## Usage

1. Start the application:

npm start


2. Access the application by visiting `http://localhost:5000` in your web browser.

3. You will see a simple web interface with a "Generate Image" button.

4. Click the "Generate Image" button to trigger a request to the OpenAI API for a random image.

5. Once the image is generated, it will be displayed on the web page.

6. Click the "Generate Image" button again to generate a new random image.

## Project Structure

The project has the following structure:

- `index.js`: Entry point of the application where Express.js is configured.
- `routes/index.js`: Defines the routes for the application.
- `controllers/imageController.js`: Contains the logic to generate random images using the OpenAI API.
- `public/`: Directory to serve static files, such as HTML, CSS, and client-side JavaScript.


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This project was developed using the following libraries and APIs:

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [OpenAI API](https://platform.openai.com/)
- [OpenAI JS](https://github.com/openai/openai-node)


