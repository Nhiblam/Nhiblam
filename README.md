<h1 align="center">Ihsan Mehtabuddin</h1>

<p align="center">
  <a href="mailto:ihsan510d@gmail.com">Email</a> •
  <a href="https://linkedin.com/in/ihsan-mehtabuddin-933395251">LinkedIn</a>
</p>

---

### About Me

Computer Engineering student at San Jose State University with hands-on experience in **real-time systems, distributed architectures, and embedded development**.

I build systems that operate under real-world constraints by low latency, high throughput, and high reliability.

---

### Featured Work

#### mmWave Radar Perception System (Texas Instruments), [Link](https://github.com/Nhiblam/mmWave-Radar)

* Developed a 3-radar perception system in Python using AWS EC2 with SQL database ingest and WebSockets to give real time, privacy focused birds eye view perception for robots.
* Implemented in Python a multi-stage sensor fusion pipeline combining DBSCAN for group clustering, RANSAC plane estimation, ICP pointcloud registration, and FPFH feature matching, achieving 94% object classification accuracy on real-world test data.
* Established a CI/CD workflow using Git for both client and server components, automating dependency installation, environment setup, and deployment to AWS EC2 instances using systemd services for efficient debugging and testing for our hardware for future work.
* Designed a SQLite database with WAL mode concurrent write architecture for sustained throughput of 800 writes per second with zero data loss during 6-hour stress tests so that it supports 3 parallel sensor feeds
* Implemented an option in Python for UDP or AWS IoT ingestion bridge for streaming sensor data into a centralized database, decoupling hardware input from visualization and processing layers.

#### Online Banking Platform, [Link](https://github.com/TheHS1/OnlineATM)

* Full-stack banking application built in Python, HTML, and CSS using Django framework, supporting multi-user account management, transaction history, fund transfers, deposit checks by user submitted images, and admin implement. 
* Designed and managed a relational database using MySQL to store user accounts, balances, and transaction history, ensuring accurate and real-time data updates during transfers and withdrawals.
* Implemented image processing using OCR (OpenCV + easyOCR) for check deposits by extracting text from uploaded images, reducing manual input and improving deposit efficiency.
* Integrated multi-factor authentication and credential validation to enhance account security and protect sensitive financial data.
* Deployed the web-based banking application on an Oracle Cloud VM, configuring a Linux server environment to host the backend and ensure remote accessibility.
* Configured Nginx on an Oracle Cloud instance to handle incoming HTTP requests and route traffic to the Django application, improving performance and reliability.

#### MSP432 Real-Time Firmware, [Link](https://github.com/Nhiblam/MSP432-Embedded-Work)

* Built embedded systems programs on an MSP432 microcontroller to control hardware, communicate with peripherals, and process real-time data.
* Implemented UART communication using both register-level access and software bit-banging, allowing reliable data transmission while understanding timing constraints and baud rate limitations.
* Configured ADC with timer-triggered sampling to capture voltage and temperature data, enabling accurate and consistent real-time sensor measurements.
* Optimized data transfer using DMA instead of CPU-driven methods, significantly reducing energy consumption and improving overall system efficiency.
* Developed multitasking applications using an RTOS to control multiple LEDs at different rates, demonstrating real-time scheduling and concurrent task execution.
* Designed PWM-based control to adjust LED brightness through duty cycle modulation, achieving smooth output transitions and precise hardware control.

---

### Contact

* Email: [ihsan510d@gmail.com](mailto:ihsan510d@gmail.com)
* LinkedIn: https://linkedin.com/in/ihsan-mehtabuddin-933395251
