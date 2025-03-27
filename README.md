# JMeter Performance Testing 🚀
This repository contains JMeter test plans for API and UI load testing.  
It includes various tests such as load, stress, spike, and endurance testing.

## 📂 Folder Structure
- `tests/` → JMeter `.jmx` files
- `data/` → CSV files for dynamic test data
- `results/` → Test reports and logs
- `scripts/` → Scripts for automation
- `dashboard/` → Grafana dashboards

## 🔧 How to Run Tests
1️⃣ Run with JMeter GUI:
jmeter -t tests/test_name.jmx -l results/test_name_results.jtl

2️⃣ Run in CLI Mode:
jmeter -n -t tests/test_name.jmx -l results/test_name_results.jtl -e -o results/

📊 Analyzing Results
•	View results/load_test_report.html for performance metrics.
•	Used Grafana for real-time monitoring with InfluxDB.

🛠️ Requirements
•	JMeter 5.x
•	Java 8+
•	Optional: Grafana, InfluxDB for monitoring
