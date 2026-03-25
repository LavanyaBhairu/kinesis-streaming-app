# 🚀 AWS Kinesis Real-Time Streaming App

## 📌 Overview
This project demonstrates a **real-time data streaming pipeline** using AWS Kinesis.  
It includes a **producer service** that sends data to a Kinesis stream and a **consumer service** that processes the streamed data.

---

## 🧠 Architecture

Producer → AWS Kinesis Stream → Consumer

---

## ⚙️ Tech Stack

- Node.js
- AWS Kinesis
- AWS SDK (JavaScript)
- (Optional) Terraform for infrastructure

---

## 🔥 Features

- Real-time data streaming
- Scalable and event-driven architecture
- Fault-tolerant design
- Modular producer and consumer services

---

## 📁 Project Structure
kinesis-streaming-app/
│
├── producer/
│ └── producer.js
│
├── consumer/
│ └── consumer.js
│
├── .env.example
├── README.md
└── .gitignore


---

## How to Run

### 1. Clone Repository
git clone https://github.com/YOUR_USERNAME/kinesis-streaming-app.git
cd kinesis-streaming-app

### 2. Install Dependencies
cd producer
npm install

cd ../consumer
npm install

### 3. Configure Environment Variables

Create .env file:

AWS_REGION=ap-south-1
STREAM_NAME=your-stream-name
ACCESS_KEY=your-access-key
SECRET_KEY=your-secret-key

### 4. Run Producer
node producer.js

### 5. Run Consumer
node consumer.js

### Output Example
Producer sends real-time events
Consumer reads and logs processed data
