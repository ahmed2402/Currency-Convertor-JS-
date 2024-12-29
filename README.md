# Currency Converter

## Overview
This project is a fully functional currency converter that allows users to convert amounts between different currencies in real-time. The app fetches live exchange rates using the ExchangeRate API and provides an intuitive interface for user interaction.

## Features
- Enter an amount to be converted.
- Select source and target currencies using dropdown menus.
- Automatically updates exchange rates on page load and upon user interaction.
- Displays currency flags alongside the currency codes for better user experience.
- Fetches live exchange rates from the ExchangeRate API.
- Responsive design for seamless use across devices.

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Styling the interface for a modern and clean look.
- **JavaScript**: Functionality to fetch data from the API, update the DOM, and handle user input.
- **ExchangeRate API**: For fetching live currency exchange rates.
- **Font Awesome**: For adding icons (e.g., arrow icon for the conversion direction).

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd currency-converter
   ```

3. Deploy the project locally or on any hosting platform. Alternatively, view the live version deployed on Vercel.

## How to Use
1. Enter the amount to be converted in the input field.
2. Select the source currency from the "From" dropdown menu.
3. Select the target currency from the "To" dropdown menu.
4. Click the **Get Exchange Rate** button.
5. View the converted amount and the current exchange rate in the displayed message.

## API Key Configuration
This project uses the ExchangeRate API. Replace the API key in the `baseUrl` variable in the `cc.js` file with your own API key:
```javascript
const baseUrl = "https://v6.exchangerate-api.com/v6/<your-api-key>/pair/";
```

## Live Demo
The project is live on Vercel. Check it out here:
[Currency Converter on Vercel]([currency-convertor-js-psi.vercel.app](https://currency-convertor-js-psi.vercel.app/))

## File Structure
```
.
├── index.html          # Main HTML file
├── style.css           # Stylesheet for the project
├── codes.js            # JavaScript for handling currency conversion logic
├── cc.js               # JavaScript for updating the interface
├── countryList.js      # Country and currency codes mapping
```

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [ExchangeRate API](https://www.exchangerate-api.com/) for providing currency exchange data.
- [Font Awesome](https://fontawesome.com/) for icons.
- [Flags API](https://flagsapi.com/) for country flags.

---
For any issues or suggestions, feel free to contact the maintainer or open an issue in the repository.
```