# 📘 FinOps Project Analysis Report – June 2025

This report analyzes mock AWS usage across three fictional cloud teams (Data, App, DevOps). The dataset simulates daily costs over two weeks, allowing for cost allocation, service breakdown, and cloud optimization recommendations.

---

## 🔍 Insights

- **Highest Cost Contributor:**  
  The **Data Team** incurred the highest spend (~55%) due to EC2 and Athena usage.

- **App Team Efficiency:**  
  Leanest cost profile by relying on cost-effective services like Lambda and S3. Optimization focus could target Lambda invocation volume.

- **DevOps Usage Profile:**  
  Notable spending on CloudWatch and CloudFormation. Worth reviewing S3 Glacier storage if backup frequency can be reduced.

- **Shared Service Visibility:**  
  Tools like CloudWatch used across teams should have tagged or allocated charges to improve accountability.

---

## 📈 Visuals Summary

- **Pie Chart:** Total cost by team highlights proportional usage.
- **Stacked Column Chart:** Daily service spend shows spending patterns and identifies days of high EC2 or Lambda activity.

---

## ✅ Recommendations

1. **Adopt Resource Tagging Policy**  
   Enforce tags like `Team=`, `Env=`, and `Project=` for better cost attribution.

2. **Set Service Budgets**  
   Budget thresholds for EC2, Athena, and CloudWatch can detect anomalies early.

3. **Implement Scheduled Start/Stop for EC2**  
   The Data Team’s EC2 hours suggest idle time — scheduled automation could save 30%+.

4. **Consider FinOps Dashboards**  
   Set up a centralized Power BI or QuickSight dashboard for real-time visibility.

---

## 📎 Next Steps

- Expand the dataset with multiple accounts or environments.
- Practice CUR-based reporting and integrate tagging automation.
- Explore the FinOps Foundation’s **FOCUS** data model for deeper simulations.

---
**Author:** Awwal  
**Focus Area:** FinOps (Cloud Financial Operations)  
**Tools:** Google Sheets, AWS Cost Simulation, Excel Charts  
