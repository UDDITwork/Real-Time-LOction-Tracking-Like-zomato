Real-Time Tracker is a web application designed to provide a seamless tracking experience similar to Zomato's rider tracking feature. It offers real-time location updates and an intuitive map view, ensuring user can monitor rider effortlessly.

Features
Real-Time Location Updates: Track the live location of riders personnel.
Interactive Map View: Visualize delivery routes using OpenStreetMap and Leaflet.
User Authentication: Separate login/signup pages for users and delivery personnel.
Marker Management: Users can create and manage markers on the map.
Technologies Used
Frontend: React, React-Leaflet, React Router
Backend: Node.js, Express.js
Database: MongoDB
Mapping: Leaflet, OpenStreetMap
Installation
To run this project locally, follow these steps:

Clone the repository:https://github.com/UDDITwork/Real-Time-LOction-Tracking-Like-zomato
cd real-time-tracker
Install dependencies:

npm install
Set up MongoDB:

Create a MongoDB database and obtain your connection string.

Update the MongoDB URI in .env file:

MONGODB_URI=your_mongodb_connection_string
Start the development server:

npm start
Open your browser and navigate to http://localhost:3000.

Folder Structure
real-time-tracker/
├── client/         # Frontend React app
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.js
│       ├── index.js
│       └── ...
├── server/         # Backend Node.js app
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── ...
├── .env            # Environment variables
├── package.json    # Project dependencies and scripts
└── README.md       # Project overview, installation guide, and usage instructions
Usage
User Interface: Navigate to the login/signup pages for users and delivery personnel.
Map View: View real-time location updates and delivery routes on the map.
Contributing
Contributions are welcome! Fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Leaflet: Open-source JavaScript library for mobile-friendly interactive maps.
OpenStreetMap: Open data mapping service.
Happy Coding!
