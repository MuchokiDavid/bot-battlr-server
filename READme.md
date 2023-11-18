# JSON Server

## Overview

This project sets up a simple JSON Server to serve as a mock API for your frontend development needs. With this project, you can easily simulate a backend server without the need for a full-fledged backend implementation.

The project is designed to be hosted on [Render](https://render.com/), a cloud platform that simplifies deployment and scaling.

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/dmmuchoki7/bot-battlr-server.git
   ```

2. Navigate to the project directory:

   ```bash
   cd bot-battlr-server
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

## Configuration

You can customize the JSON data by modifying the `db.json` file in the project root. Add your own JSON data to simulate different API endpoints.

## Usage

To start the JSON Server, run the following command:

```bash
npm start
```

This will start the server at `http://localhost:4000`.

## Deploying on Render

1. Create an account on [Render](https://render.com/) if you haven't already.

2. Click the "+" button on your Render dashboard to create a new service.

3. Choose the GitHub repository where you cloned this project.

4. Configure the following settings:

   - **Environment**: Set NODE_ENV to production.
   - **Build Command**: `npm install && npm run build`
   - **Start Command**: `npm start`

5. Click "Create Web Service."

6. Render will automatically build and deploy your JSON Server. Once deployed, you can access your server at the provided URL.

## Contributing

If you have suggestions or improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [JSON Server](https://github.com/typicode/json-server): The core JSON Server library.
- [Render](https://render.com/): Simplifying deployment and scaling.