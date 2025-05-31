# now-check-ab-test
Analyzing the impact of a new NOW account product using A/B testing

# 🧪 A/B Test Analysis: NOW Check Account Impact

This project evaluates the impact of a newly launched **NOW check account** product on key customer behaviors using simulated data. The analysis mimics a real-world scenario where customers are offered different product incentives (e.g., bonuses, gifts) and compares outcomes across groups.

---

## 🎯 Objectives

- Determine if the NOW account increased:
  - 📈 Customer retention (60-day)
  - 💰 Initial deposit amounts
  - 🎁 Bonus redemption engagement
- Apply proper statistical testing to validate findings

---

## 📊 Dataset

The dataset was simulated to reflect realistic customer behavior before and after the launch of the NOW account product. It includes:

- `customer_id`
- `application_date`
- `is_now_account` (treatment vs control)
- `received_bonus`, `redeemed_bonus`
- `initial_deposit`
- `retained_60_days` (binary retention indicator)

📁 File: `data/simulated_data.csv`

---

## 🧪 Methods

- **Two-proportion z-tests** for retention and bonus redemption rates
- **T-tests** for comparing deposit amounts
- **Segmented analysis** of bonus redemption impact on retention
- **Data visualization** using Matplotlib and Seaborn

---

## 📈 Key Insights

| Metric                     | NOW Account | Non-NOW Account | Uplift |
|---------------------------|-------------|-----------------|--------|
| Retention (60 days)       | 75%         | 60%             | +15%   |
| Avg Initial Deposit       | ~$1,500     | ~$1,000         | +$500  |
| Bonus Redemption Rate     | 60%+        | —               | N/A    |

> 🎯 **Conclusion**: The NOW check account had a clear positive impact on retention and deposit behavior. Bonus redemption was strongly correlated with customer stickiness.

---

## 📂 Project Structure

