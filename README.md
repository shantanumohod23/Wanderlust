# Wanderlust

Wanderlust is a travel booking platform similar to Airbnb, built with Node.js, Express, MongoDB, and Cloudinary. It allows users to sign up, create listings, browse available properties, and book stays. Cloudinary is used to manage and store images for the listings.

**[Live Demo](https://wanderlust-t94q.onrender.com/listings)**

## Features

- **User Authentication**: Secure login and signup using Passport.js.
- **Create Listings**: Users can add their own property listings with images uploaded to Cloudinary.
- **Browse Listings**: Users can view available listings by different criteria.
- **Booking System**: Users can book accommodations by selecting dates.
- **Responsive UI**: Clean, mobile-friendly interface built with EJS and custom CSS.

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: Passport.js, Passport-Local, Passport-Local-Mongoose
- **Image Upload**: Cloudinary, Multer, Multer-Storage-Cloudinary
- **Frontend**: EJS, HTML, CSS
- **Environment Variables**: dotenv
- **Session Management**: Express-session
- **Others**: Joi (validation), connect-flash (messages), method-override (HTTP methods)

## Installation

To get a local copy up and running, follow these simple steps:

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/wanderlust.git
```

### 2. Install dependencies:

```bash
cd wanderlust
npm install
```

### 3. Set up environment variables:

Create a `.env` file in the root directory and add the following:

```
DB_URI=your_mongo_db_connection_string
CLOUDINARY_URL=your_cloudinary_url
SESSION_SECRET=your_session_secret
```

### 4. Open the application in the browser:

Visit `http://localhost:3000` to access the app locally.

## Deployment

The app is deployed on Render and can be accessed at:

**[Live Demo](https://wanderlust-t94q.onrender.com/listings)**

## API Routes

- `GET /listings`: Displays all listings.
- `GET /listings/new`: Form to create a new listing.
- `POST /listings`: Create a new listing.
- `GET /listings/:id`: View details of a specific listing.
- `GET /listings/:id/edit`: Edit an existing listing.
- `PUT /listings/:id`: Update a listing.
- `DELETE /listings/:id`: Delete a listing.
- `POST /login`: User login.
- `POST /logout`: User logout.
- `GET /register`: User registration form.
- `POST /register`: User registration.

## Acknowledgments

- Cloudinary for providing image storage and management.
- Passport.js for handling user authentication.
- Mongoose for MongoDB object modeling.

