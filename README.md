# Retail Inventory Optimization System

A sophisticated multi-agent AI system for optimizing retail inventory management with real-time analytics and visualization capabilities.

## 🌟 Features

- **Multi-Agent AI System**
  - Intelligent inventory management
  - Real-time decision making
  - Automated reordering system
  - Predictive demand forecasting

- **Interactive Dashboards**
  - Streamlit-based real-time visualization
  - FastAPI support for backend services
  - Memory-efficient data processing
  - Advanced analytics and reporting

- **System Monitoring**
  - Real-time performance metrics
  - Memory usage tracking
  - Agent communication monitoring
  - System health indicators

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Virtual environment tool (venv recommended)
- PostgreSQL (for data storage)
- Docker (optional, for containerized deployment)

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd retail-inventory-optimization
```

2. Create and activate virtual environment:
```bash
   python -m venv inventory_env
# Windows
& C:\Users\abhir\Downloads\Dataset\inventory_env\Scripts\Activate.ps1
# Linux/Mac
source inventory_env/bin/activate
   ```

3. Install dependencies:
```bash
   pip install -r requirements.txt
   ```

### Running the System

1. Start the dashboard:
```bash
python run_dashboard.py --dashboard-type=streamlit --port 8501
```

2. Access the dashboard:
- Open your browser and navigate to `http://localhost:8501`

## 💻 Usage

### Dashboard Navigation

1. **Overview Page**
   - System health metrics
   - Real-time status monitoring
   - Recent alerts and notifications

2. **Inventory Management**
   - Real-time inventory levels
   - Stock filtering and search
   - Order management
   - Restock recommendations

3. **Analytics**
   - Performance metrics
   - Trend analysis
   - Predictive analytics
   - Custom reporting

4. **Agent Monitoring**
   - Agent status tracking
   - Communication visualization
   - Decision history
   - Performance optimization

## 🛠️ Configuration

### Environment Variables

Create a `.env` file with the following variables:
```
DATABASE_URL=postgresql://user:password@localhost:5432/db_name
API_KEY=your_api_key
MEMORY_LIMIT=8192
PORT=8501
```

### Command Line Options

- `--dashboard-type`: Choose between 'streamlit' or 'fastapi' (default: streamlit)
- `--port`: Specify custom port (default: 8501)
- `--host`: Set host address (default: localhost)
- `--memory-limit`: Set memory limit in MB

## 🧪 Testing

Run the test suite:
```bash
# Unit tests
python -m pytest tests/

# Integration tests
python test_integration.py

# Performance tests
python run_tests.py
```

## 🔍 Debugging

### Common Issues

1. **Port Conflicts**
   - Use `--port` to specify different port
   - Check port availability with `netstat`

2. **Memory Issues**
   - Monitor through Memory Dashboard
   - Adjust `--memory-limit`
   - Enable efficient data loading

3. **Database Connection**
   - Verify PostgreSQL service is running
   - Check connection string in `.env`
   - Ensure proper permissions

## 📦 Deployment

### Docker Deployment

1. Build and run with Docker Compose:
```bash
docker-compose up --build
```

2. Access the application:
- Dashboard: `http://localhost:8501`
- API: `http://localhost:8000`

## 🔐 Security

- End-to-end encryption for sensitive data
- Role-based access control
- Comprehensive audit logging
- Secure API authentication
- Regular security updates

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Support

For support and queries:
- Create an issue in the repository
- Contact the development team
- Check documentation in `/docs`

## 🔮 Future Enhancements

- Advanced AI/ML model integration
- Enhanced visualization capabilities
- Extended agent ecosystem
- Improved debugging tools
- Advanced analytics features

## 📊 System Architecture

- **Frontend**: Streamlit, FastAPI
- **Backend**: Python
- **Database**: PostgreSQL
- **AI**: Multi-Agent System
- **Monitoring**: Prometheus
- **Alerting**: Grafana

