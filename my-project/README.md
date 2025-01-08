# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Currency Converter Application
Overview
Realtime currency conversion React application. Favorites - Currency swapper  responsiveness styled with tailwind CSS.
Functionalities
real time Currency conversion
Ability to add or remove Favorite currency.
swap from -to - Currencies
store your favourites across all time -with help of Local storage
Full Responsive- design-for devices.
 Technologies Applied
react-app
Tailwind CSS
frankfurter's Api
React Icons
Getting Started Clone this repository into
bash
git clone https://github.com/yourusername/currency-converter.git
cd currency-converter
Install Dependencies using
bash
npm install
Run app on
basH
npm start
Your default web browser, open http://localhost:3000. Usage
Select currencies from the From and To dropdowns.
Enter an amount in the input.
Click Get Exchange Rate to see a result.
Add to/remove from favorites by clicking the star.
Swap currencies by clicking the swap button.
API Reference
Available Currencies: GET https://api.frankfurter.app/currencies
Currency Conversion: GET https://api.frankfurter.app/latest?amount=<AMOUNT>&from=<FROM>&to=<TO>
Deployment
To build the app:
bash
npm run build
Deploy the build/ folder on platforms like Netlify or Vercel.
Acknowledgments
Frankfurter API
React and Tailwind CSS