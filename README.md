# 🌐 TraceMap - Visual Network Route Analyzer

## 🚀 Overview

TraceMap is an interactive network visualization tool that helps you understand how your data travels across the internet! With TraceMap, you can:

- 🌐 Visualize network routes between your device and any destination
- 📊 Analyze hop-by-hop latency and packet loss
- 🔍 Identify potential network bottlenecks
- 🗺️ See geolocation data for each network hop
- 📱 Access from any device with responsive design

## 📦 Project Structure

### 🖥️ Frontend (Next.js)

The frontend provides an intuitive interface for visualizing network traces:
- Interactive map showing route paths
- Detailed hop information panels
- Historical trace comparison
- User authentication for saving traces

### ⚙️ Backend (Node.js)

The backend handles:
- Network trace execution (traceroute/MTR)
- IP geolocation lookup
- Data processing and analysis
- API for frontend communication

## 🛠️ Installation Guide

### 🏠 Local Setup

#### Frontend
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

#### Backend
```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Start the server
npm run start
```

### 🐳 Docker Setup

For a quick and easy setup, use Docker Compose:

```bash
# Build and start all services
docker-compose up

# To run in detached mode
docker-compose up -d

# To stop all services
docker-compose down
```

## 🧪 Using TraceMap

1. 🌟 Navigate to http://localhost:3000 in your browser
2. 🎯 Enter a target domain or IP address
3. 🚀 Start the trace analysis
4. 📊 Explore the visualization and data

## 🤝 Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.