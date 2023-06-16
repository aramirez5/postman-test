<p align="center">
  <img alt="Postman" src="https://upload.wikimedia.org/wikipedia/commons/c/c2/Postman_%28software%29.png">
</p>

![Node.js](https://img.shields.io/badge/Node.js-18.16.0-brightgreen.svg)
![Postman](https://img.shields.io/badge/Postman-10.15.1-orange.svg)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Postman Test
Welcome to the Postman Test repository! This repository contains a project that demonstrates how to execute a Postman collection using a workflow of Github Actions.

## 📋 Overview
Postman is a popular tool for testing and documenting APIs. It provides a user-friendly interface to send requests, inspect responses, and validate API behavior. This project serves as a guide to help you understand and get started with writing tests using Postman.

## 🚀 Getting Started
To get started with the Postman Test project, follow these steps:

1. Clone the repository:

```sh
git clone https://github.com/aramirez5/postman-test.git
```

1. Install NodeJS:

We need to install the lastest LTS version of node. You can download it [HERE](https://nodejs.org/).

2. Install Newman and the reporter:

```sh
npm install -g newman
```

```sh
npm install -g newman-reporter-htmlextra
```

3. Run the tests:

Execute the entire collection with this command:

```sh
newman run "collections/api_sports.postman_collection.json" -r htmlextra,cli
```

## 🤝 Contributing
Contributions to the Postman Test project are welcome! If you find any issues or have suggestions for improvements, please open an issue on the GitHub repository.

If you'd like to contribute code, please fork the repository, make your changes, and submit a pull request. Your contributions will help enhance the project for everyone!

## 📄 License
This repository is licensed under the MIT License. Feel free to use, modify, and distribute the code and resources in this repository according to the terms of the license.

## 📧 Contact
If you have any questions or need assistance with the Postman Test project, you can reach out to the repository owner by opening an issue on the GitHub repository.

Happy testing with Postman! 🚀

