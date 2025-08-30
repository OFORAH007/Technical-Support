# 📊 Technical Support Dashboard – Power BI Project  

##  Project Overview  
This project analyzes **technical support tickets** using **Power Query, DAX, and Power BI**.  
The dashboards provide insights into:  
- Ticket volume and trends  
- SLA compliance (first response & resolution)  
- Agent performance  
- Customer interaction channels  
- Common support topics  

The purpose of the project is to enable **data-driven decision making** for support operations and improve service delivery efficiency.  

---

##  Dataset Sources & Description  
The dataset is derived from internal **technical support logs** with a total of **2,330 tickets**.  

**Key Features of the Dataset:**  
- **Ticket Details**: Ticket ID, Created Date & Time, Status, Priority  
- **Channels**: Email, Chat, Phone  
- **Ticket Topics**: Bug Report, Product Setup, Pricing & Licensing, Training, Purchasing & Invoicing, etc.  
- **SLA Metrics**: First Response SLA, Resolution SLA (Achieved vs Violated)  
- **Agent Information**: Assigned Agent, Number of Interactions, Customer Rating  

---

##  Objectives  
The primary objectives of this project were:  

1. Track and visualize **ticket volumes** by time, source, and priority.  
2. Measure **SLA compliance rates** for both first response and resolution times.  
3. Compare **ticket distribution** across communication channels.  
4. Assess **agent performance** using workload, SLA adherence, and ratings.  
5. Identify **frequent ticket topics** and product groups with recurring issues.  
6. Provide **recommendations** to optimize support operations.  

---

##  Tools Used  
- **Power Query** → For data extraction, transformation, and cleaning.  
- **DAX (Data Analysis Expressions)** → For building calculated measures, KPIs, and aggregations.  
- **Power BI Desktop** → For dashboard development, visualization, and reporting.  

---

##  Data Preparation & Cleaning  
The raw dataset underwent several transformation steps in **Power Query**:  

1. **Data Import & Merging**: Imported multiple support logs and combined into a unified dataset.  
2. **Date/Time Standardization**: Converted created date and time into usable formats for trend analysis.  
3. **Categorization**: Grouped tickets by priority (High, Medium, Low) and source (Email, Chat, Phone).  
4. **Derived Fields**: Created calculated columns for SLA compliance (Achieved/Violated).  
5. **Error Handling**: Removed duplicates, null values, and inconsistent entries.  
6. **Data Modeling**: Established relationships between ticket facts, agent dimension, and SLA metrics.  

---

##  Exploratory Data Analysis (EDA)  

###  Ticket Trends  
- **Monthly Distribution**: Ticket volumes fluctuated across months, peaking around Q2.  
- **Weekday vs Weekend**: **84.9% of tickets** were created on weekdays, confirming higher support demand during business hours.  

###  Source Distribution  
- **Email**: 52.96%  
- **Chat**: 36.48%  
- **Phone**: 10.56%  

### 📌 Product Groups  
- **Ready-to-use Software** → 1,010 tickets  
- **Custom Software Development** → 644 tickets  
- **Training & Consulting** → 331 tickets  
- **Other Requests** → 345 tickets  

---
<img width="1535" height="858" alt="Tech Support 01" src="https://github.com/user-attachments/assets/10b5cb53-2255-48ee-af3c-f50d31d0f4c6" />
<img width="1534" height="858" alt="Tech Support 02" src="https://github.com/user-attachments/assets/5b088246-c89f-4522-9a1b-dfcf0f38832c" />
<img width="1535" height="862" alt="Tech Support 03" src="https://github.com/user-attachments/assets/1477cdd9-0415-4505-ad5b-a9426422203b" />
<img width="1535" height="856" alt="Tech Support 04" src="https://github.com/user-attachments/assets/f1599814-bf90-444c-9ed2-6b138fd8e578" />

##  Data Analysis Dashboards  

The project features **four key dashboards** built in Power BI:  

1. **Ticket Volume Dashboard**  
   - Ticket trends (monthly/weekly/hourly)  
   - Distribution by channel, priority, and product group  

2. **SLA Dashboard**  
   - SLA Achieved vs Violated (First Response & Resolution)  
   - SLA breakdown by source and ticket priority  

3. **Agent Performance Dashboard**  
   - Tickets handled per agent  
   - SLA adherence per agent  
   - Customer ratings and average resolution times  

4. **Global Ticket Dashboard**  
   - Ticket creation statistics across countries  
   - Topic distribution by geography  

---

##  Key Findings & Insights  

### Findings  
- **SLA Violations**:  
  - **First Response**: 13.35% violated  
  - **Resolution SLA**: 33.61% violated  
- **Channel Weakness**:  
  - Chat tickets accounted for **16.57% of SLA violations** (highest source of breaches).  
- **Priority Tickets**:  
  - Low-priority tickets were responsible for **17.34% of SLA breaches**.  
- **Agent Workload**:  
  - Some agents were overloaded, leading to SLA delays.  
- **Customer Ratings**:  
  - Performance varied significantly, suggesting skill/training gaps among agents.  

### Recommendations  
1. **Redistribute workload** across agents to balance ticket handling.  
2. **Address SLA breaches** in low-priority tickets to reduce backlog.  
3. **Improve Chat support** response times with dedicated teams.  
4. **Provide targeted training** for underperforming agents.  
5. **Link customer satisfaction** more directly with SLA performance metrics.  

---

## ⚠ Limitations  
- Dataset only covers **a single reporting period**, limiting long-term trend analysis.  
- SLA targets were applied uniformly across all ticket types, though some topics may realistically require different thresholds.  
- Customer ratings were sparse and may not fully capture customer experience.  

---

##  Conclusion  
This Power BI project demonstrates how **support ticket logs** can be transformed into **actionable insights** with the help of **Power Query, DAX, and interactive dashboards**.  

The findings highlighted inefficiencies in **SLA compliance, agent workload distribution, and chat support performance**. By implementing the recommendations, the support team can:  
- Reduce SLA violations  
- Improve agent performance  
- Enhance customer satisfaction  
- Optimize overall support efficiency  

---

##  References  
- [Microsoft Power BI Documentation](https://learn.microsoft.com/power-bi/)  
- [DAX Guide](https://dax.guide/)  
- Internal Technical Support Dataset (2023–2025)  

---

