# AgriPrice Predictor

A web application that predicts agricultural commodity prices using AI/ML. Built with React, Flask, and SARIMA time series modeling.

## Features

- Real-time price tracking for various agricultural commodities
- Interactive price history visualization
- Price prediction for up to 12 months
- Beautiful dark-themed UI with Material-UI components
- Responsive design for all devices

## Tech Stack

### Frontend
- React with TypeScript
- Material-UI (MUI)
- Chart.js for data visualization
- Axios for API calls

### Backend
- Flask (Python)
- Pandas for data manipulation
- SARIMA model for time series prediction
- Flask-CORS for handling cross-origin requests

## Setup Instructions

### Backend Setup

1. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Flask server:
```bash
python app.py
```

The server will start at http://localhost:5000

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will open at http://localhost:3000

## API Endpoints

- GET `/api/commodities` - List all available commodities
- GET `/api/data?commodity={name}` - Get historical price data for a commodity
- GET `/api/stats?commodity={name}` - Get price statistics for a commodity
- POST `/api/predict` - Get price predictions for a commodity

## Screenshots

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/96faebf8-4a30-4a9c-a749-f15420db1c91" />
<img width="1894" height="1079" alt="image" src="https://github.com/user-attachments/assets/2505ecfc-fb09-4cdf-bc3f-7663ac7c1e45" />



## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
