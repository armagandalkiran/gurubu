# Gurubu

[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://github.com/Trendyol/gurubu/blob/main/LICENSE)

## Simple, Fast, and Practical Task Estimation and Tech Grooming

### Agree with your teammates quickly and reliably! Start by setting up a room.

Gurubu is a tool designed to streamline task estimation grooming sessions and prioritize tasks using a room-based, user-friendly approach. With a single click, users can create a room, invite team members, and start estimating story points or voting on multiple metrics for tech grooming.

![Ekran Resmi 2023-11-07 17 06 17](https://github.com/Trendyol/gurubu/assets/77741597/7531e45a-c43d-4558-be2f-4285cf1f6ec5)

## Features


- **One-Click Room Setup:** Quickly create a dedicated room for your task estimation or tech grooming session.

![Ekran Resmi 2023-11-07 17 06 34](https://github.com/Trendyol/gurubu/assets/77741597/4cc8b311-aa16-4cf8-923c-29fc75939599)

- **User-Friendly Interface:** Easily enter your name and join a room, making collaboration simple and efficient.

- **Story Point Estimation:** Streamline the process of estimating story points to better plan and manage your project.

- **Tech Grooming:** Prioritize tasks effectively by allowing users to vote on multiple metrics.

![Ekran Resmi 2023-11-07 17 08 39](https://github.com/Trendyol/gurubu/assets/77741597/2b913495-a3a3-4d0c-b580-9078a7c62d1e)

## Getting Started

### Requirements

- Node.js and yarn (To manage project dependencies for the frontend and the backend)

### Frontend Installation

1. Clone this repository to your local machine:
```shell
https://github.com/Trendyol/gurubu.git
```
2. Navigate to the frontend directory:
```shell
cd gurubu-client
```
3. Create .env variable root of the project and add this variable:
```shell
NEXT_PUBLIC_API_URL="http://localhost:5000"
```
4. Install the dependencies:
```shell
yarn 
```
5. Start the frontend application:
```shell
yarn dev
```

The frontend application should now be running at http://localhost:3000.

### Backend Installation

1. Clone this repository to your local machine:
```shell
https://github.com/Trendyol/gurubu.git
```
2. Navigate to the backend directory:
```shell
cd gurubu-client
```
3. Create .env variable root of the project and add this variable:
```shell
CLIENT_URL="http://localhost:3000"
```
4. Install the dependencies:
```shell
yarn 
```
5. Start the backend application:
```shell
yarn start:server:dev
```

The backend server should now be running at http://localhost:5000.




