# Personal Website Monitor

A lightweight, automated Python script designed to check the uptime and availability of my frequently used websites.
This project was built as a practical application to learn cloud monitoring concepts, HTTP requests, and exception handling.

## 🚀 Features

* **Status Checking:** Sends HTTP GET requests to a customizable list of URLs to verify if they are active.
* **Graceful Error Handling:** Utilizes `try/except` blocks to prevent the script from crashing when encountering dead links, network timeouts, or DNS errors.
* **Detailed Logs:** Outputs a timestamped scan report directly to the console, concluding with a quick summary of total online and offline sites.

## 🛠️ Built With

* **Python 3**
* **Requests Library** - Used for sending HTTP requests and managing timeout thresholds.

## 📦 Getting Started

### Prerequisites

You will need Python 3 installed on your machine. You will also need to install the `requests` library. You can install it via pip:

```bash
pip install requests
