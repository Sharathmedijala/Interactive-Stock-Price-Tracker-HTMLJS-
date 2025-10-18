# 📈 Interactive Stock Price Tracker

An **interactive web application** built with **HTML, Tailwind CSS, and Chart.js** that allows users to view **real-time stock price data** and **30-day historical trends** using the **Alpha Vantage API**.

![App Screenshot](https://user-images.githubusercontent.com/placeholder/stock-tracker-preview.png)

---

## 🚀 Features

✅ **Real-Time Stock Data** — Displays live stock prices, changes, and volume.  
✅ **Beautiful UI** — Built using Tailwind CSS for a clean, responsive design.  
✅ **Dynamic Chart** — Line chart visualizing the last 30 days of closing prices.  
✅ **Error Handling** — Shows user-friendly messages when symbols or data are invalid.  
✅ **Loading Spinner** — Smooth feedback while fetching data.  
✅ **Responsive Layout** — Works seamlessly on desktop and mobile screens.  
✅ **Default Stock Display** — Loads IBM stock data on page load.

---

## 🧰 Tech Stack

- **Frontend:** HTML5, CSS3 (Tailwind CSS), JavaScript (ES6+)
- **Charting:** [Chart.js](https://www.chartjs.org/)
- **API:** [Alpha Vantage API](https://www.alphavantage.co/)
- **Fonts:** Google Fonts (Inter)

---

## 📦 Setup Instructions

### 1. Clone the Repository

If you’ve uploaded this to GitHub, clone it to your local machine:

```bash
git clone https://github.com/<your-username>/Interactive-Stock-Price-Tracker.git
cd Interactive-Stock-Price-Tracker


### 2. Get a Free API Key

Sign up at **[Alpha Vantage](https://www.alphavantage.co/support/#api-key)** and generate a free API key.

---

### 3. Add Your API Key

Open the HTML file in VS Code and replace the placeholder with your key:

```javascript
const API_KEY = 'YOUR_ALPHA_VANTAGE_API_KEY'; // Replace this line
```

Example:

```javascript
const API_KEY = 'ABC123XYZ456';
```

---

### 4. Run the App

Simply open the file `index.html` in your web browser.

💡 Tip: You can also use a local server (e.g., VS Code Live Server extension) for a smoother experience.

---

## 📊 Usage

1. Enter a **stock symbol** (e.g., `AAPL`, `MSFT`, `GOOGL`).
2. Click **"Get Stock Data"**.
3. View:

   * Company symbol
   * Latest price
   * Daily change & percent change
   * Open, High, Low, Volume
4. Scroll down to view a **30-day closing price chart**.

---

## 🧠 How It Works

1. Fetches daily time series data using:

   ```plaintext
   https://www.alphavantage.co/query?function=TIME_SERIES_DAILY&symbol=XYZ&apikey=YOUR_KEY
   ```
2. Fetches real-time quote using:

   ```plaintext
   https://www.alphavantage.co/query?function=GLOBAL_QUOTE&symbol=XYZ&apikey=YOUR_KEY
   ```
3. Parses JSON data to extract prices and volumes.
4. Displays data dynamically on the page and renders a Chart.js graph.

---

## 🧩 File Structure

```
Interactive-Stock-Price-Tracker/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── (Optional assets)
```

---

## 🖌️ UI Highlights

* **Tailwind CSS** ensures a modern, mobile-friendly layout.
* **Chart.js** provides smooth, interactive graphs.
* Clean color palette with hover effects for a polished look.

---

## ⚠️ Notes

* **Alpha Vantage free tier** limits you to **5 API calls per minute** and **500 per day**.
* If you hit the rate limit, wait a few minutes before fetching again.
* Ensure you have a stable internet connection for real-time data.

---

## 🌐 Live Demo (Optional)

If deployed (e.g., on GitHub Pages or Netlify), include your link here:

👉 [View Live Demo](https://<your-username>.github.io/Interactive-Stock-Price-Tracker/)

---

## 💪 Future Enhancements

* [ ] Add support for multiple chart types (candlestick, bar).
* [ ] Include more technical indicators (SMA, EMA, RSI).
* [ ] Enable dark mode.
* [ ] Save favorite stocks locally.

---

## 👨‍💻 Author

**Sharath Medijala**
📧 [your.email@example.com](mailto:your.email@example.com)
🔗 [GitHub Profile](https://github.com/<your-username>)
💼 [LinkedIn](https://linkedin.com/in/<your-linkedin>)

---

## 📝 License

This project is open-source and available under the **MIT License**.

```
MIT License © 2025 Sharath Medijala
```

---

✨ **Interactive. Lightweight. Real-time.**
Track your favorite stocks with style 📊💙

```

---

Would you like me to also create a **`README.md` version with badges** (like "Made with HTML • Tailwind CSS • Chart.js • API: Alpha Vantage") for a more professional GitHub appearance?
```
