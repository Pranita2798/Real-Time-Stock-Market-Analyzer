# Real-Time Stock Market Analyzer

A beautiful, production-ready stock market analysis application built with React, TypeScript, and modern web technologies. Features real-time price tracking, technical indicators, portfolio management, and news sentiment analysis.

![Stock Market Analyzer](https://images.pexels.com/photos/6801648/pexels-photo-6801648.jpeg?auto=compress&cs=tinysrgb&w=1200&h=600&fit=crop)

## ✨ Features

### 📈 Real-Time Stock Tracking
- Live price updates every 5 seconds
- Support for major stocks (AAPL, GOOGL, MSFT, AMZN, TSLA, META, NVDA, NFLX)
- Color-coded price changes with trend indicators
- Volume and market cap information

### 📊 Interactive Charts
- Beautiful line charts with Chart.js
- Multiple timeframes (1D, 1W, 1M, 3M, 1Y)
- Smooth animations and hover interactions
- Responsive design for all screen sizes

### 🔧 Technical Analysis
- **RSI (Relative Strength Index)** - Overbought/oversold signals
- **MACD** - Moving Average Convergence Divergence
- **Moving Averages** - SMA 20, SMA 50, EMA 12, EMA 26
- Real-time indicator calculations

### 💼 Portfolio Management
- Add/remove stocks from your portfolio
- Track shares, purchase price, and current value
- Real-time profit/loss calculations
- Portfolio performance overview

### 📰 News & Sentiment Analysis
- Latest news headlines for selected stocks
- Sentiment analysis with positive/negative/neutral scoring
- Time-based news filtering
- External link integration

### 🎨 Beautiful Design
- Modern, professional interface
- Responsive grid layout
- Smooth transitions and hover effects
- Clean typography and spacing
- Intuitive navigation with tabbed interface

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd stock-market-analyzer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Chart.js** - Interactive charts and graphs
- **Lucide React** - Beautiful icons
- **Vite** - Fast build tool and dev server

### Data & APIs
- **Axios** - HTTP client for API requests
- **Date-fns** - Date manipulation utilities
- Mock data service (easily replaceable with real APIs)

## 📁 Project Structure

```
src/
├── components/           # React components
│   ├── StockCard.tsx    # Individual stock display cards
│   ├── StockChart.tsx   # Interactive price charts
│   ├── TechnicalIndicators.tsx # Technical analysis display
│   ├── Portfolio.tsx    # Portfolio management
│   ├── NewsPanel.tsx    # News and sentiment analysis
│   └── PeriodSelector.tsx # Time period selection
├── services/            # Business logic and API calls
│   └── stockService.ts  # Stock data service
├── types/              # TypeScript type definitions
│   └── stock.ts        # Stock-related interfaces
├── App.tsx             # Main application component
├── main.tsx           # Application entry point
└── index.css          # Global styles
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory for API configuration:

```env
VITE_ALPHA_VANTAGE_API_KEY=your_api_key_here
VITE_NEWS_API_KEY=your_news_api_key_here
```

### API Integration
The application currently uses mock data for demonstration. To integrate with real APIs:

1. **Stock Data**: Replace mock service with Alpha Vantage, Yahoo Finance, or similar
2. **News Data**: Integrate with NewsAPI, Finnhub, or similar news providers
3. **Update the `stockService.ts`** file with real API endpoints

## 📊 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎯 Usage

### Adding Stocks to Portfolio
1. Navigate to the **Portfolio** tab
2. Click **Add Stock** button
3. Enter stock symbol, shares, and purchase price
4. View real-time profit/loss calculations

### Viewing Technical Analysis
1. Select a stock from the **Overview** tab
2. Navigate to **Charts** tab for detailed analysis
3. View RSI, MACD, and moving averages
4. Switch between different time periods

### Reading News & Sentiment
1. Select a stock symbol
2. Navigate to **News** tab
3. View latest headlines with sentiment scores
4. Click external link icons to read full articles

## 🔮 Future Enhancements

- [ ] Real-time WebSocket connections
- [ ] Advanced charting with candlestick patterns
- [ ] Options and derivatives tracking
- [ ] Cryptocurrency support
- [ ] Mobile app version
- [ ] User authentication and data persistence
- [ ] Advanced portfolio analytics
- [ ] Custom alerts and notifications
- [ ] Social trading features
- [ ] AI-powered trading suggestions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Chart.js](https://www.chartjs.org/) for beautiful charts
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Lucide](https://lucide.dev/) for icons
- [Pexels](https://www.pexels.com/) for stock photos

