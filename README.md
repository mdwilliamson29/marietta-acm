# WebcamGPT-Vision

Maretta-WebcamGPT-Vision is a lightweight web application that enables users to process images from their webcam using OpenAI's GPT-4o's vision capabilities. The AI is instructed to return the name and description of objects that are held in someone's hand.

![image](https://github.com/user-attachments/assets/3d4697b0-d5e4-42bd-b8fc-58ca9a84c7f8)


## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a modern web browser.
- You have Node.js and npm installed. https://nodejs.org/en npm install -g npm
- You have obtained an API key from OpenAI for GPT-4o usage.

## Installation

To install WebcamGPT-Vision, follow these steps for the correct version:

### Node.js Version

1. Clone the repository:
   ```sh
   git clone https://github.com/mdwilliamson29/marietta-acm
   ```
2. Navigate to the `js-version` directory.
3. Run `npm install` to install the dependencies.
4. Create a `.env` file in the root of `js-version` directory and add your OpenAI API key:
   ```
   OPENAI_API_KEY=YOUR_DEFAULT_API_KEY
   ```
5. Start the server with `node server.js`.
6. Access the application through your web browser at `http://localhost:3000` (or the port you configured).

## Acknowledgements

- Thanks to (https://github.com/bdekraker/webcamgpt-vision) for providing the initial application.
