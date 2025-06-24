# JMeter Performance Testing – Kabir Raj Panthy

This project demonstrates performance and load testing using **Apache JMeter**. The test plan simulates multiple users accessing a sample API to assess performance under load.

## 🧪 Test Plan

- **Tool:** Apache JMeter
- **Test Type:** Load Testing
- **Target:** Sample REST API (e.g., https://jsonplaceholder.typicode.com/posts)
- **Users Simulated:** 50
- **Ramp-up Time:** 10 seconds
- **Loop Count:** 10

## 📁 Files

- `load_test_plan.jmx` – JMeter test plan
- `README.md` – Project documentation

## ▶️ How to Run

1. Download and install [Apache JMeter](https://jmeter.apache.org/).
2. Open `load_test_plan.jmx` in JMeter.
3. Click the green **Start** button to run the test.
4. View results in:
   - **Graph Results**
   - **Summary Report**
   - **View Results Tree**

## 📊 Sample Metrics

- Average response time
- Throughput (requests/second)
- Error % rate
- Min/Max response time

---

Feel free to tweak the configuration and target URL based on your test goals.
