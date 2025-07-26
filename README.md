Real-Time Eye Movement Tracking Platform - High-Level Design

This architecture captures real-time eye movement data from the client via WebSocket, streams it through Kafka for scalable ingestion, and stores raw data in S3 for durable, cost-effective and highly scalable solution to persist large volumes of unprocessed data. Processed data is saved into TimescaleDB for efficient time series analytics, while the client interacts with the analytics service for visualization and insights.

<img width="893" height="497" alt="image" src="https://github.com/user-attachments/assets/76b4ef84-cb51-45e0-94ea-2d6628ea28e7" />
