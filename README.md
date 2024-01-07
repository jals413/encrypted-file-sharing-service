
# Encrypted File Sharing Service

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [How to Use](#how-to-use)
4. [Technologies Used](#technologies-used)
5. [Setup Locally](#setup-locally)
6. [How to Contribute](#how-to-contribute)
7. [Links](#links)
8. [License](#license)

## Description
The Encrypted File Sharing Service is a peer-to-peer file sharing application that prioritizes secure data transfer. It allows users to share files with end-to-end encryption, ensuring that shared data is accessible only to intended recipients.

## Features
- **Password Protection:** Users can set passwords for their files, adding an extra layer of security.
- **Encryption:** Utilizes bcrypt for robust encryption, safeguarding file contents during transfer.
- **User-Friendly Interface:** Designed for ease of use, ensuring a smooth file-sharing experience.

## How to Use
1. **Uploading a File:** Choose a file to share, set a password for encryption, and upload it to the service.
2. **Sharing:** Once uploaded, a unique link is generated which can be shared with the recipient.
3. **Downloading:** The recipient uses the link to download the file. The correct password must be entered to access and decrypt the file.

## Technologies Used
- **EJS:** A templating language used to generate HTML with plain JavaScript. It's utilized for creating dynamic views in the application.
- **Express:** A fast, unopinionated, minimalist web framework for Node.js, used for handling server-side logic and routing.
- **Mongoose:** A MongoDB object modeling tool designed to work in an asynchronous environment. It's used for database operations.
- **Multer:** A Node.js middleware for handling `multipart/form-data`, primarily used for uploading files.
- **Bcrypt:** A library to help hash passwords, providing a secure way to store and compare user passwords.
- **Dotenv:** A zero-dependency module that loads environment variables from a `.env` file into `process.env`, making it easier to manage sensitive configuration options.


## Setup Locally
To set up the project on your local machine, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/jals413/encrypted-file-sharing-service.git
   ```
2. Navigate to the directory:
   ```
   cd encrypted-file-sharing-service
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Start the server:
   ```
   npm start
   ```
5. Access the application via `http://localhost:3000` (or the configured port).

## How to Contribute
We welcome contributions of all forms. Here's how you can contribute:

1. **Reporting Issues:** Use the [Issue Tracker](https://github.com/jals413/encrypted-file-sharing-service/issues) to report bugs or suggest enhancements.
2. **Submitting Pull Requests:** For code contributions, please follow these steps:
   - Fork the repository.
   - Create a new branch (`git checkout -b my-new-feature`).
   - Make your changes and test them.
   - Commit your changes (`git commit -am 'Add some feature'`).
   - Push the branch (`git push origin my-new-feature`).
   - Open a pull request.

## Links
- [GitHub Repository](https://github.com/jals413/encrypted-file-sharing-service)
- [Issues](https://github.com/jals413/encrypted-file-sharing-service/issues)
- [Pull Requests](https://github.com/jals413/encrypted-file-sharing-service/pulls)
- [Commit Activity](https://github.com/jals413/encrypted-file-sharing-service/graphs/commit-activity)

## License
This project is made available under the MIT License. For more details, see the [LICENSE.md](LICENSE.md) file.
