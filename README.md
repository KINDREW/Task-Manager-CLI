# Task Manager CLI

A command-line interface (CLI) tool for managing tasks and todos directly from your terminal. This tool allows you to create, read, update, and delete tasks using a set of simple commands.

## Features

- **Add Tasks**: Create new todos with a name and description.
- **Read Tasks**: View all existing todos.
- **Update Tasks**: Modify existing todos or delete them if marked as completed.
- **Delete Tasks**: Remove todos based on their unique code.

## Installation

To install and use the Task Manager CLI tool globally, follow these steps:

1. **Clone the Repository**

   ```sh
   git clone https://github.com/KINDREW/Task-Manager-CLI.git
   ```

2. **Install Dependencies**

   Ensure you have Node.js installed. Then, install the necessary dependencies:

   ```sh
   npm install
   ```

3. **Link the CLI Tool**

   To install the CLI tool globally on your system:

   ```sh
   npm install -g .
   ```

## Usage

After installing, you can use the CLI tool with the following commands:

- **Add a New Task**

  ```sh
  todo add
  ```

  Follow the prompts to enter the task name and details.

- **Read All Tasks**

  ```sh
  todo read
  ```

  This command will list all existing todos.

- **Update a Task**

  ```sh
  todo update
  ```

  Enter the code of the task you want to update, and follow the prompts to modify its details. You can also choose to delete the task if its status is marked as completed.

- **Delete a Task**

  ```sh
  todo delete
  ```

  Enter the code of the task you want to delete. If the task exists, it will be removed.

## Configuration

This CLI tool uses MongoDB for storing tasks. Ensure you have MongoDB installed and running. Configure the MongoDB connection URI by creating a `.env` file in the root directory of the project with the following content:

```env
MONGO_URI=your_mongodb_connection_string
```

Replace `your_mongodb_connection_string` with your actual MongoDB connection URI.

## Dependencies

- **chalk**: For styling terminal output.
- **commander**: For handling command-line arguments and commands.
- **dotenv**: For loading environment variables.
- **inquirer**: For prompting user input.
- **mongoose**: For interacting with MongoDB.
- **nanoid**: For generating unique IDs.
- **ora**: For displaying spinners.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue if you find any bugs or have suggestions for improvements.

## Contact

For any questions or feedback, please reach out to [your email address](mailto:kindrew99@gmail.com).

```

```
