# Cloud-Native-Financial-Risk-Assessment-project
This project implements a cloud-native API designed to analyse the risk and profitability of trading strategies using financial simulations. The system distributes tasks across Google App Engine (GAE), AWS Lambda, and Amazon EC2, enabling scalable and efficient computation.

---

## 📁 Project Contents

- `app/index.py`: Main Flask API route (for GAE).
- `app/lambda_handler.py`: AWS Lambda handler function.
- `app/ec2_compute.py`: Script to run heavy analysis on EC2.
- `app/utils.py`: Utility/helper functions.
- `cloud_app_deployment/app.yaml`: Configuration file for GAE deployment.
- `requirements.txt`: List of required Python libraries.
- `COMM034_Report.pdf`: Final academic report documenting the project.
- `test/`: Contains API test scripts and a Postman collection.

---

## 📊 Project Overview

This project was developed to demonstrate how cloud-native architectures can support real-time, scalable risk analytics. It includes:

- Value-at-Risk (VaR) calculations at 95% and 99% confidence levels
- Profit and loss (PnL) summaries from simulated trading strategies
- Dynamic scaling of compute resources across AWS and GCP

---

## 🚀 Technologies Used

- **Python 3.9**
- **Flask** for API routing
- **Google App Engine (GAE)** for web interface
- **AWS Lambda** for serverless event-based tasks
- **Amazon EC2** for heavy computation
- **Boto3**, **Requests**, **Matplotlib**, **Pandas**

---

## 🧪 Key Outputs

- VaR at 95%: `-0.0419`
- VaR at 99%: `-0.1191`
- Total PnL: `-4.516`
- GAE cost (est.): `$150/month`
- EC2 cost (est.): `$72/month`
- Lambda cost (est.): `< $1/month`

---

## 📎 Report

For full explanation of the architecture, methodology, results, and cost analysis:  
📄6847190 Atharva Sapkal COMM0034 pdf

---

## 👨‍💻 Author

**Atharva Sapkal**  

---

## 📌 Disclaimer

This project was developed for academic purposes only.  
Not intended for real-world financial decision-making.
