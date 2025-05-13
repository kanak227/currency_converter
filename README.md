# Currency Converter

A simple React application that allows users to convert between different currencies using real-time exchange rates.

## Features

- Convert between various international currencies
- Real-time exchange rates
- Swap conversion direction with a single click
- Clean, responsive user interface

## Technology Stack

- React.js
- Tailwind CSS
- Vite

## API Used

The application uses the following API for currency conversion:

```javascript
"https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/${currency}.json"
```

## Project Structure

- `src/components` - Contains reusable UI components
- `src/hooks` - Contains custom React hooks, including [useCurrencyInfo.js](./src/hooks/useCurrencyinfo.js) for fetching currency data

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## How It Works

The application fetches current exchange rates using the currency API and allows users to convert amounts between different currencies. Users can also swap the source and target currencies with a single click.