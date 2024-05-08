# Azure Search OpenAI Demo - Backend

This is the backend for the Azure Search OpenAI Demo. It's built with Python and uses the Quart framework for asynchronous web applications. The backend is designed to handle user queries and generate responses using different approaches defined in the `approaches` directory.

## Getting Started

1. Clone the repository
2. Navigate to the `azure-search-openai-demo/app/backend` directory
3. Install dependencies with `pip install -r requirements.txt`
4. Start the server with `python app.py`

## Project Structure

The main file is `app.py`, which sets up and starts the Quart server. It imports and uses various Azure services and OpenAI services.

### app.py

This file sets up and starts the Quart server. It imports and uses various Azure services and OpenAI services. It also sets up the Quart server with CORS and OpenTelemetry middleware.

### approaches/approach.py

This file defines the `Approach` class, which is the base class for all approach classes in the `approaches` directory. Each approach class defines a different way of processing user queries and generating responses. You can customize the behavior of the Backend App by modifying the `run` method of the approach classes.

## API

The server has several routes, each corresponding to a different functionality of the application. The routes are defined in `app.py`.

## Running the Server

To start the server, navigate to the `azure-search-openai-demo/app/backend` directory and run `python app.py`. The server will start and listen for incoming connections.

## Dependencies

The dependencies for the backend application are listed in the `requirements.txt` file. You can install them with `pip install -r requirements.txt`.

## Contributing

Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.