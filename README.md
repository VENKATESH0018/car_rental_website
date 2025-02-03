# Car Rental Website

## Overview
This is a fully functional Car Rental Website built using React.js, Tailwind CSS, JavaScript, Firebase, and REST API. The platform allows users to browse available cars, book rentals, and manage their reservations with ease.

## Features
- **User Authentication** (Firebase Authentication)
- **Car Listings** with filtering and sorting
- **Real-time Database** integration (Firebase)
- **Booking Management**
- **REST API Integration** for fetching and updating data
- **Responsive Design** with Tailwind CSS
- **User Dashboard** for tracking bookings
- **Admin Panel** (Optional) for car and booking management

## Tech Stack
- **Frontend:** React.js, Tailwind CSS, JavaScript
- **Backend:** Firebase (Authentication, Firestore Database)
- **API Integration:** REST API

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-rental-website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-rental-website
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up Firebase:
   - Create a Firebase project and enable Authentication & Firestore Database
   - Add your Firebase configuration to `.env.local`:
     ```env
     REACT_APP_FIREBASE_API_KEY=your_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_project_id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
     REACT_APP_FIREBASE_APP_ID=your_app_id
     ```
5. Start the development server:
   ```bash
   npm start
   ```

## Usage
- Users can sign up, log in, and browse available cars.
- Users can select cars and book them based on availability.
- Bookings are stored in Firebase Firestore.
- Admins (if implemented) can manage car listings and bookings.

## Deployment
You can deploy this project using platforms like **Vercel** or **Netlify**:
```bash
npm run build
```
Upload the `build/` folder to your hosting provider.

## Contributing
Feel free to fork the repository and submit pull requests for improvements.



