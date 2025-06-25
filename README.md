# 🧠 AI - powered-Testing-Metrics-Dashboard
An interactive Power BI dashboard with built-in AI assistant (TestGenie) that delivers real-time insights across test cycles, defect trends, and requirement traceability.

___

# 🧠 AI - powered Testing Metrics Dashboard

___

🧾 **Overview**  
The **AI-Enabled Testing Metrics Dashboard** is a centralized analytics solution designed to transform how QA teams, project managers, and stakeholders visualize and interact with testing data. Built using **Power BI**, **SQL**, and **Excel**, this interactive dashboard provides **end-to-end traceability**, **defect analytics**, and **test execution summaries**. 

What sets this dashboard apart? An embedded **AI assistant called “TestGenie”**—a natural language Q&A tool that allows users to query testing metrics in plain English.

___

## 🎯 Objectives

- Bridge the gap between scattered test data and real-time decision-making.
- Provide **visibility across testing lifecycles**: Epics → Features → Stories → Tasks → Defects.
- Integrate an **AI chatbot** (TestGenie) to reduce manual effort in retrieving insights.
- Empower QA leads and stakeholders to track **defect leakage**, **automation coverage**, and **test effectiveness**.
- Facilitate **fast, actionable decisions** in reviews, retrospectives, and leadership meetings.

___

## 🧠 My Contribution 

I was **solely responsible** for the **Test Summary Dashboard** and the development of the **AI chatbot – TestGenie**, which includes:

- Designing KPIs like Test Cycle Time, Test Effectiveness, Feature Blockage, and Automation Coverage.
- Building AI-powered Q&A experience using **Power BI’s natural language capabilities**.
- Integrating backend relationships across 5 layers of testing artifacts for end-to-end data traceability.
- Optimizing dashboard interactivity and layout for executive reviews.

___

## 🛠 Technologies Used

- **Microsoft Excel** – Mock dataset preparation
- **SQL** – Data modeling & relationships
- **Power BI** – Dashboard development, DAX measures, AI Q&A
- **Natural Language Processing** – AI Assistant via Power BI Q&A engine

___

## 🧩 Data Model

Structured on **five key entities**:

**Epic → Feature → User Story → Task → Defect**

- Built using 1:Many relationships for deep drill-downs
- Supports KPIs like Defect Leakage, Mean Time to Resolve (MTTR), Automation Coverage

___

## 📊 Dashboard Modules

<img width="1403" alt="image" src="https://github.com/user-attachments/assets/19a564e8-ab8d-4ef1-b3f8-6d5ae69ae7f5" />

### 📌 1. Requirements Traceability Matrix
- Hierarchical trace: Program → Epic → Story → Task → Defect
- Color-coded status indicators
- Instantly flags missing ownership or delays

___

<img width="1476" alt="image" src="https://github.com/user-attachments/assets/60ce65f0-fda5-4e30-bbf9-ef40d0835b04" />

### 🐞 2. Defect Dashboard
- Track defect health by Severity, Age, Status
- Key KPIs: Defect Leakage, Resolution Rate, Recurrence Rate, MTTD

___

<img width="1250" alt="image" src="https://github.com/user-attachments/assets/9bda7528-0296-48f3-a12a-cc29e2a912a0" />

### 📦 3. Test Summary Dashboard
- Real-time entity counts and test health
- KPIs: Test Cycle Time, Test Effectiveness, Feature Blockage, Automation Coverage

___

## 🤖 AI Assistant – TestGenie

> 💬 Ask:
> - “Pending defects in Epic EP-004?”
> - “Which features are blocked?”

___

## 🧭 Implementation Timeline

| Phase | Description |
|-------|-------------|
| 1 | Requirement Gathering & KPI Finalization |
| 2 | Data Modeling using Excel & SQL |
| 3 | Wireframing & Layout Design |
| 4 | Power BI Development & Visual Building |
| 5 | DAX Logic & Filter Logic |
| 6 | AI Q&A Integration & Testing |
| 7 | Final Presentation |

___

## 📎 Files Included

Full walkthrough of dashboard structure, visuals, and TestGenie demo - [Testing Metrics Dashboard.pptx](https://github.com/user-attachments/files/20898538/Testing.Metrics.Dashboard.pptx)

___

## ✅ Outcome

- Revolutionized QA reporting by delivering an interactive, AI-powered insights platform that supports real-time decision-making.
- Eliminated manual reporting overhead through seamless integration of the TestGenie AI assistant, enabling natural language queries for testing metrics.
- Streamlined cross-functional collaboration with visual dashboards that enhanced clarity and alignment during stakeholder reviews and retrospectives.
- Achieved full lifecycle visibility by mapping testing artifacts from epics to defects—boosting traceability, automation maturity, and defect governance.
- Accelerated delivery confidence by proactively identifying risks, blockers, and testing gaps across the software development lifecycle.
