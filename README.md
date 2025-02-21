Crypto Gainers
A simple web app that displays the top 10 daily cryptocurrency gainers from the top 350 coins by market cap, using data from the CoinGecko API.
Live Demo
Features
Displays real-time data for the top 10 cryptocurrencies with the highest 24-hour price gains
Includes:
Rank
Name
Symbol
Current Price (USD)
24h Price Change (%)
Market Cap (USD)
24h Trading Volume (USD)
Auto-refreshes every 5 minutes
Manual refresh button
Loading states and error handling with retry logic
Responsive design
Technologies Used
HTML5: Structure
CSS3: Styling
JavaScript: Fetching and displaying data
CoinGecko API: Free cryptocurrency data source
GitHub Pages: Hosting
How It Works
Fetches data from CoinGecko's API (https://api.coingecko.com/api/v3/coins/markets)
Sorts the top 350 coins by 24-hour price change percentage
Displays the top 10 gainers in a table
Updates automatically every 5 minutes and handles errors with up to 3 retries
Setup and Deployment
Prerequisites
A modern web browser
Internet connection (for API calls)
GitHub account (for deployment)
Local Development
Clone the repository:
bash
git clone https://github.com/cooldog-dev/crypto-gainers.git
Open index.html in a browser:
Double-click the file, or
Use a local server (e.g., VS Code Live Server) for better testing
Deploy to GitHub Pages
Push the code to your repository:
bash
git add .
git commit -m "Initial commit"
git push origin main
Enable GitHub Pages in repository settings:
Go to "Settings" > "Pages"
Set Source to main branch and root folder (/)
Access the site at: https://cooldog-dev.github.io/crypto-gainers/
Usage
Open the URL in your browser
Wait for the table to populate with crypto data
Click "Refresh Data" for manual updates
The app auto-refreshes every 5 minutes when the page is visible
Troubleshooting
Blank page: Check browser console (F12) for errors
API errors: 
May occur due to CoinGecko rate limits (10-50 requests/minute)
Wait and retry, or reduce refresh frequency
Not updating: Ensure the page is visible (auto-refresh pauses when tab is hidden)
Future Improvements
Add sorting by columns
Include more data (e.g., 7d change)
Add a search/filter feature
Store data locally for offline viewing
Customize refresh interval
Contributing
Feel free to fork this repository and submit pull requests with improvements!
License
This project is open-source and available under the MIT License (LICENSE).
Credits
Built with ❤️ by cooldog-dev
Data provided by CoinGecko
