# Firebase CRUD Operations with Python

This project demonstrates how to perform CRUD (Create, Read, Update, Delete) operations in Firebase using Python and the Firebase Admin SDK.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)

## Introduction

Firebase is a powerful cloud platform that provides a range of services for building and scaling web and mobile applications. In this project, we explore how to interact with Firebase's backend services programmatically using Python and the Firebase Admin SDK. We cover the process of setting up Firebase, initializing the Firebase Admin SDK, and performing CRUD operations in Realtime Database or Firestore.

## Prerequisites

- Python 3.x
- `firebase-admin` package
- Firebase project with the necessary services enabled

## Installation

1. Fork and clone the [repository](https://github.com/prajeshElEvEn/pybase-crud):

   ```bash

   git clone <repo_url>

   ```

2. Navigate to the project directory:

   ```bash

   cd pybase-crud

   ```

3. Create a virtual environment:

   ```bash

   python -m venv venv

   ```

4. Activate the virtual environment:

   ```bash

   source venv/bin/activate

   ```

5. Install the required dependencies:

   ```bash

    pip install -r requirements.txt

   ```

6. Configure Firebase Admin SDK:
   - Generate a private key file (service account key) in your Firebase project settings.
   - Rename the generated JSON file to `serviceAccountKey.json`.
   - Place the `serviceAccountKey.json` file in the project directory.

## Usage

1. Update the Firebase project configuration in the `main.py` file with your own project credentials.

2. Run the Python script:

   ```bash

   python main.py

   ```

3. Follow the prompts in the terminal to perform CRUD operations in Firebase.

## Author

[@prajesh](https://github.com/prajeshElEvEn)
