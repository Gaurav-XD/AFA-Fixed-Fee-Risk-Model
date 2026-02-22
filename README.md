🧾 AFA Fixed Fee Risk Model
📊 Pricing & Margin Sensitivity Analysis for Professional Services
🔍 Executive Summary

This project develops a structured financial risk model for evaluating fixed-fee (Alternative Fee Arrangement – AFA) engagements in professional services such as law firms and consulting firms.

Unlike hourly billing, fixed-fee pricing introduces financial exposure because revenue is fixed while cost varies with hours and staffing composition. This model enables pre-approval evaluation of margin sustainability and break-even risk.

🎯 Business Problem

Professional services firms face the following risks under fixed-fee engagements:

Revenue is predetermined

Actual hours may exceed estimates

Senior resource involvement increases cost

Margin erosion occurs before break-even

Without structured analysis, firms may approve engagements that are profitable on paper but financially risky in execution.

🧠 Analytical Framework Applied

This model applies core pricing analytics principles:

Concept	Purpose
Break-even Analysis	Identify hour threshold where profit = 0
Margin Threshold Analysis	Identify when margin falls below target
Cost Sensitivity Modeling	Measure impact of hour increases
Resource Mix Optimization	Evaluate staffing cost structure impact
Scenario Testing	Simulate financial exposure before approval
🏗 Model Architecture
1️⃣ Assumptions Layer

Structured input framework including:

Fixed Fee Revenue

Estimated Hours

Target Margin

Resource Cost per Level (Partner / Senior / Junior)

Resource Mix (%)

Weighted Average Cost Calculation

2️⃣ Base Case Financial Evaluation

Automatically calculates:

Total Project Cost

Expected Profit

Expected Margin

Break-even Hours

Margin Erosion Threshold

3️⃣ Risk & Sensitivity Engine

Evaluates:

Profit impact across hour scenarios

Margin classification:

Above Target

Below Target

Loss

Visual profit sensitivity chart

📈 Visual Output Example

💼 Strategic Application

This model supports pricing teams in:

Evaluating fixed-fee financial exposure

Protecting target margins

Stress-testing engagement assumptions

Supporting data-driven commercial negotiations

Balancing revenue and cost risk

📌 Key Insight Demonstrated

Margin risk begins before break-even.
Even profitable engagements may underperform if target margins are not protected.

Resource mix decisions materially impact:

Break-even threshold

Safety buffer

Financial flexibility

🚀 Tools Used

Microsoft Excel

Structured financial modeling


Scenario-based risk analysis

📎 Repository Structure

afa-fixed-fee-risk-model/
│
├── excel-model/
├── screenshots/
└── docs/
