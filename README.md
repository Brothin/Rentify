# RENTIFY - Where Renting Meets Simplicity

Building a Real Estate website using the MERN stack involves creating a full-stack application with MongoDB, Express.js, React.js, and Node.js.

## LIVE URL

https://property-sell.onrender.com/

## Technology Stack

Backend - Node Js, Express Js, Socket Io, Mongoose, Jwt.

Database - Mongodb.

Fronted - React Js, React Router Dom, React Hook Form, Firebase, Tailwind Css, Socket Io Client.

## Key Features

### User Authentication:

Allow users to register and log in. Ensure that certain features, like adding listings or favoriting properties, are accessible only to authenticated users.

### CRUD Operations:

#### Create:

Implement a form to allow users to add new property listings. This form should include details like property name, address, description, price, type (sale or rent), number of bedrooms, bathrooms, etc.

#### Read:

Display property listings on the homepage or on a dedicated listings page. Each listing should show key information and a link to view more details.

#### Update

Allow users to edit their own property listings. Include validation to ensure data consistency.

#### Delete

Provide an option for users to delete their listings.

### Search and Filters:

Implement a search bar to allow users to search for properties based on keywords like location, type, or price range. Include filters for refining search results, such as filtering by property type, number of bedrooms, bathrooms, etc.

### Real time conversation and local notification:

Use Socket IO to implement real-time communication between the server and the client. This will allow users to receive notifications when new listings are added or when other.

### Image Upload:

Allow users to upload images for their property listings. Display these images in a gallery or carousel on the listing details page.

### User Dashboard

Provide a user dashboard where users can manage their property listings, view favorites, and edit their profile.

### Responsive Design

This website is responsive, making it accessible and user-friendly across various devices, including desktops, tablets, and mobile phones.

### Error Handling and Validation

Implement thorough error handling and validation on the server and client sides to ensure data integrity and a smooth user experience.

### Pagination

If you have a large number of listings, implement pagination to improve page load times and the user experience.

## Screenshots
### Home Page
![Screenshot (282)](https://github.com/Brothin/Rentify/assets/78947331/76685fe0-a060-4e0c-8739-0e7a294e4c9d)
### Login Page
![Screenshot (281)](https://github.com/Brothin/Rentify/assets/78947331/84006770-3096-484d-a204-866c2dd7d2fc)
### Profile Page
![Screenshot (283)](https://github.com/Brothin/Rentify/assets/78947331/de7d3e49-9dab-40b9-baf6-8981b6978b32)
### Property Listing Page
![Screenshot (284)](https://github.com/Brothin/Rentify/assets/78947331/66fafbef-a7a8-4456-a707-1cfcbd3c605d)
### Property Details Page
![Screenshot (286)](https://github.com/Brothin/Rentify/assets/78947331/7c54ff59-7c83-4ef9-89ab-c147c18b50b9)
### Property Searching Page
![Screenshot (287)](https://github.com/Brothin/Rentify/assets/78947331/6d835e33-6372-4164-b50a-dc133281f202)
### Chatting Page
![Screenshot (288)](https://github.com/Brothin/Rentify/assets/78947331/afe7c924-a2aa-471e-a381-611022759068)

## Getting Started

### Clone the repository

```
git clone https://github.com/Brothin/Rentify.git
```

```
cd Rentify
```

### You need

• Node

• MongoDB or Mongo Atlas

• NPM

### Create your MongoDB account and database/cluster

• Create your own MongoDB account by visiting the MongoDB website and signing up for a new account.

• Create a new database or cluster by following the instructions provided in the MongoDB documentation. Remember to note down the "Connect to your application URI" for the database, as you will need it later. Also, make sure to change with your own password.

• Add your current IP address to the MongoDB database's IP whitelist to allow connections (this is needed whenever your ip changes).

### Create .env file

Create a .env file in the client folder to store your credentials. This file will store environment variables for the frontend to run.

```
VITE_FIRIBASE_API_KEY=""
```

Create a .env file in the api folder to store your credentials. This file will store environment variables for the backend to run.

```
NODE_ENV=local
PORT=3000
MONGO="
JWT_SECRET=supersecretjwtkey
```

### Installation

To install and run this project -
Install dependencies using npm in client folder and run frontend side of application.

```
cd client
npm install
npm start
```

Install dependencies using npm in api folder and run server side of application.

```
cd api
npm install
npm run dev
```
