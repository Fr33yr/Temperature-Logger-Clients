# 📡 Project Hub – Multi-Client, Server, and NodeMCU Integration  

This repository serves as a central hub for managing and linking the various components of our project, including mobile and desktop clients, the Node.js server, and firmware for the NodeMCU board. Each component plays a crucial role in data collection, processing, and visualization.  

## 📱 Mobile Client  
**Built with**: Kotlin (Jetpack Compose)  
**Purpose**: Provides a responsive and intuitive interface to display real-time data collected from the NodeMCU. Allows users to interact with the system on the go.  

## 🖥️ Desktop Client  
**Built with**: Tauri and React  
**Purpose**: Desktop version for a more immersive data visualization experience using React charts, leveraging the performance of Tauri to create lightweight yet powerful applications.  

## 🖧 Node.js Server  
**Built with**: Node.js (Express)  
**Purpose**: Acts as the backend, handling communication between clients and the NodeMCU. Responsible for data storage, processing, and ensuring consistent synchronization across platforms. Uses Socket.IO for real-time data visualization.  

## 🔌 NodeMCU Firmware  
**Built with**: C++ (Arduino Framework)  
**Purpose**: Directly interfaces with sensors and hardware, collecting data and sending it to the server. Forms the core of the data acquisition process.  

## 🔗 Project Goals  
- **Seamless Integration**: All components work together to provide accurate, real-time data visualization.  
- **Consistency**: Ensures that mobile, desktop, and server-side codebases stay aligned.  
- **Scalability**: The system is designed to handle increasing amounts of data and add more sensors or clients as needed.  
