# Bus Connect
Bus Connect is a vehicle telemetry system for buses. It reads CAN bus data via STM32, logs it to an SD card, and sends it through ESP32 to AWS. Data is stored in S3, queried with Athena, and visualized in Grafana to monitor metrics like engine RPM, speed, and route.
