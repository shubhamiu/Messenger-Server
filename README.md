# Messenger Server



This README provides instructions on how to set up and run the project. .

## Prerequisites

Before you begin, make sure you have Node.js and npm installed on your machine. If not, you can download and install them from [Node.js official website](https://nodejs.org/).

## Getting Started

Follow these steps to get the project up and running on your local machine for development and testing purposes.

### 1. Clone the Repository

First, clone the main application repository to your local machine using the following command:

```bash
git clone https://github.com/shubhamiu/Messenger-server.git
cd Messenger-server
```

### 2. Install Dependencies

Navigate to the project directory where the `package.json` file is located and install the necessary dependencies:

```bash
npm install
```

### 3. Start the Application

Once the dependencies are installed, you can start the application using:

```bash
npm start
```

This command will start the development server, usually accessible via `http://localhost:8800` or a similar URL provided in the terminal.

### 4. Clone and Setup the Messenger Server

In addition to this main application, which is a server that serves the chat history, conversations, and messages you need to set up the Socket server, which resides in a different repository. Clone the Messenger server repository and navigate to it:

```bash
git clone https://github.com/shubhamiu/Socket.git
```

### 5. Install Dependencies for the Messenger Server

Install the necessary dependencies for the Messenger server in the same way as for the main application:

```bash
npm install
```

### 6. Start the Messenger Server

Start the Messenger server using:

```bash
npm start
```

Ensure that the Messenger server is running correctly and listening for connections, typically on a different port specified in its configuration.

## Usage

With both the main application and the Messenger server running, you should now be able to interact with the application through your web browser and see real-time functionalities being handled by the socket server.

## Troubleshooting

If you encounter any issues during installation or running the servers, please check the following:

- Ensure that all dependencies were installed without errors.
- Check that the ports required by the application and the Messenger server are not in use.
- Consult the console output for any error messages that might indicate what went wrong.

## Contributing

We welcome contributions to both the main application and the Messenger server. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.

