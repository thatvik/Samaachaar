# Samaachaar - Government Scheme Portal

A MERN stack application that helps users discover and apply for government schemes based on their eligibility criteria.

## Features

- User Authentication (Email/Password & Google OAuth)
- Aadhaar Verification with OTP
- Profile Management
- Scheme Discovery by Category
- Eligibility-based Scheme Filtering
- Responsive Design

## Tech Stack

- **Frontend**: React.js, Material-UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Passport.js, JWT
- **Aadhaar Verification**: Custom OTP System

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/samaachaar.git
cd samaachaar
```

2. Install dependencies:
```bash
# Install backend dependencies
cd Registration_Login_Form_MERN_Stack/backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables:
Create a `.env` file in the backend directory with:
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

4. Start the development servers:
```bash
# Start backend server
cd Registration_Login_Form_MERN_Stack/backend
npm start

# Start frontend server
cd ../frontend
npm start
```

## Project Structure

```
Registration_Login_Form_MERN_Stack/
├── backend/
│   ├── models/         # MongoDB models
│   ├── routes/         # API routes
│   ├── services/       # Business logic
│   └── index.js        # Server entry point
├── frontend/
│   ├── public/         # Static files
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── context/    # React context
│   │   └── App.jsx     # Main App component
│   └── package.json
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 