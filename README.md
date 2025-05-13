# Real-Time Stock Data Streaming Application

## Project Overview
A sophisticated Python-based real-time stock data streaming application that captures live market data using WebSocket technology.

## Author : Shriniwas Kulkarni
- **PCCOE 2026 BTech CSE(AIML)**
- **Email:** [kshriniwas180205@gmail.com](mailto:kshriniwas180205@gmail.com)  
- **Phone:** +91 [8999883480]  
- **GitHub:** [github.com/Shriniwas18K](https://github.com/Shriniwas18K)  

## Technical Architecture
- **Language**: Python 3.8+
- **Data Source**: Finnhub.io WebSocket API
- **Data Storage**: CSV

## Key Features
- Real-time stock data streaming
- Multi-threaded message processing
- Robust error handling
- Continuous data logging
- Scalable design

## Prerequisites
- Python 3.8+
- Finnhub.io API Key
- Required Python Packages:
  - `websocket-client`
  - `json`
  - `threading`
  - `logging`

## Installation

### Backend Setup
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install websocket-client
   ```
3. Set up Finnhub API Key:
   - Create a `.env` file
   - Add: `API_KEY=your_finnhub_api_key`

## Configuration
- Modify `tickers` list in `task1.py` to track desired stocks
- Adjust `OUTPUT_PATH` for CSV file location

## Running the Application
1. Backend:
   ```bash
   python task1.py
   ```

## Project Structure
- `task1.py`: WebSocket data streaming script
- `op1.csv`: Output data file
- `websocket_data.log`: Application log file
- React component for data visualization

## Advanced Concepts Demonstrated
- WebSocket communication
- Concurrent processing
- Error handling
- Logging
- Data persistence
- Reactive programming

## Potential Enhancements
- Add more sophisticated error recovery
- Implement real-time dashboard
- Support dynamic ticker management

## Security Considerations
- Use environment variables for API keys
- Implement proper error logging
- Secure file handling

## Troubleshooting
- Ensure stable internet connection
- Check API key validity
- Verify Python and dependency versions

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Acknowledgments
- Finnhub.io for providing real-time stock data API
- Open-source community for supporting development
