# Crypto Hustle

Crypto Hustle is a React-based web application that provides real-time information about various cryptocurrencies. It allows users to view a list of cryptocurrencies, search for specific coins, and see their current prices in USD.

## Features

- Display a list of cryptocurrencies
- Real-time price updates for each cryptocurrency
- Search functionality to filter cryptocurrencies
- Responsive design with a side navigation bar

## Technologies Used

- React
- Vite
- CSS
- CryptoCompare API

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/crypto-hustle.git
   cd crypto-hustle
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory and add your CryptoCompare API key:
   ```
   VITE_APP_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173` to view the application.

## Project Structure

- `src/App.jsx`: Main component that fetches and displays cryptocurrency data
- `src/Components/CoinInfo.jsx`: Component for displaying individual cryptocurrency information
- `src/Components/SideNav.jsx`: Side navigation component
- `src/App.css`: Styles for the application

## API Integration

This project uses the CryptoCompare API to fetch cryptocurrency data. The API key is stored in the `.env` file and accessed using `import.meta.env.VITE_APP_API_KEY`.
