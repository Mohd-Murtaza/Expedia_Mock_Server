# Expedia Mock Server

This project implements a mock server for simulating Expedia-like data retrieval. It uses json-server to create a RESTful API with mock data, allowing developers to work on frontend applications without relying on a real backend.

## Table of Contents

- [Project Overview](#project-overview)
- [Folder Structure](#folder-structure)
- [Setup](#setup)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Data Structure](#data-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Expedia Mock Server provides a simple way to simulate data fetching for hotel information in various cities. It's particularly useful for frontend developers who need to work with realistic data while developing user interfaces for travel and booking applications.

## Folder Structure

    Expedia_Mock_Server/
    │
    ├── .gitignore
    ├── db.json
    ├── package-lock.json
    ├── package.json
    ├── README.md
    └── server.js

- `db.json`: Contains the mock data for hotels in different cities.
- `package.json` & `package-lock.json`: Define project dependencies and scripts.
- `server.js`: The main server file that sets up and runs the json-server.
- `README.md`: This file, containing project documentation.

## Setup

1. Clone the repository: git clone https://github.com/your-username/Expedia_Mock_Server.git
2. Navigate to the project directory:  cd Expedia_Mock_Server
3. Install dependencies: npm install

## Usage

To start the mock server: npm start

This will start the server on `http://localhost:4000`.

## API Endpoints

The server provides the following endpoints:

- `/delhi`: Get hotel information for Delhi
- `/goa`: Get hotel information for Goa
- `/mumbai`: Get hotel information for Mumbai

Example: `http://localhost:4000/delhi`
deployed link: `https://expedia-mock-server.onrender.com/`

## Data Structure

Each city's data is an array of hotel objects. Each hotel object contains information such as:

- `id`
- `city`
- `heading1` (hotel name)
- `heading2` (area)
- `img1`, `img2`, `img3`, `img4` (image URLs)
- `text1`, `text2`, `text3`, `text4` (various descriptive texts)
- `rating`
- `review`
- `no_of_reviews`
- `price1`, `price2`

For the exact structure, refer to the `db.json` file.

## Contributing

Contributions to improve the mock server or extend its functionality are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License. See the `package.json` file for details.

---

For any additional information or queries, please open an issue in the GitHub repository.
