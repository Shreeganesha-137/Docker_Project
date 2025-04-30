# Docker_Project
# Name Display Website

A simple web application that allows users to input their name and display a personalized greeting. Built with Node.js, Express, and Docker for easy deployment.

## Features
- Input field to enter a name
- Displays a greeting with the entered name
- Responsive design with clean UI
- Containerized with Docker for consistent deployment

## Prerequisites
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Project Structure
- `index.html`: Main HTML file for the front-end
- `style.css`: CSS styles for the UI
- `server.js`: Node.js/Express server to serve the application
- `Dockerfile`: Docker configuration for building the image
- `docker-compose.yml`: Docker Compose configuration for running the container
- `package.json`: Node.js dependencies and scripts

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd name-display


Build and run the Docker container:

docker-compose up --build

Open your browser and navigate to http://localhost:3000.

Usage

Enter a name in the input field.

Click the "Display" button to see a greeting like "Hello, [Your Name]!".

To stop the application, press Ctrl+C in the terminal and run:

docker-compose down

Development
To modify the application, edit the files in the project directory. Changes will be reflected due to the volume mapping in docker-compose.yml.



To run without Docker (requires Node.js):

npm install
npm start

License

MIT License. See LICENSE for details.

Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes.


# How to Run
1. Create a new directory and save all files above in it.
2. Ensure Docker and Docker Compose are installed.
3. Run `docker-compose up --build` in the terminal from the project directory.
4. Open a browser and navigate to `http://localhost:3000`.
5. Enter a name in the input field and click "Display" to see the greeting.

# Notes
- The README.md is formatted for GitHub, with clear instructions for setup and usage.
- The website uses Express.js to serve the static HTML and CSS files.
- The Dockerfile creates a lightweight Node.js container.
- docker-compose.yml simplifies running the container with port mapping.
- The application is accessible at port 3000.
- To stop the application, use `Ctrl+C` in the terminal, then run `docker-compose down`.
