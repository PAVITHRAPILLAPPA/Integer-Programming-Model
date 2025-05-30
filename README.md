# Integer-Programming-Model

---

## 📚 Case Study Background

Paulette Smith and Maureen Becker, students at State University, founded **PM Computer Services** to build and sell personal computers. They assemble computers at home with a team of students and sell them mainly to university departments and other students.

**Key Details:**
- Each employee can produce **12.7 computers** per month (regular).  
- Overtime production adds **0.6 computer/employee/month** and costs **$12** per computer.  
- Hiring new workers costs **$200**; layoffs cost **$320**.  
- Holding inventory costs **$15 per computer per month**.  
- Current workforce: **5 employees**.  
- Demand forecast for next 6 months: **63, 74, 95, 57, 68, 86** computers.

The objective is to develop a production and staffing schedule that minimizes total costs while meeting demand and ensuring no inventory remains at the end of month 6.

---

## 📁 Repository Contents

- **📄 Pavithra_Pillappa_C5_PM_Computer_Services_IP_Formulation.pdf**  
  Comprehensive Integer Programming formulation, clearly defining decision variables, objective function, and operational constraints.

- **📊 Pavithra_Pillappa_C5_PM_Computer_Services_IP_Implementation.pdf**  
  Excel-based implementation with monthly workforce, production, and inventory plans, along with sensitivity analysis to assess model robustness.

---

## 🔑 Key Features & Methodology

✅ **Integer Programming Formulation**  
- Decision variables for: employees hired and laid off, production (regular & overtime), and monthly inventory.  
- Objective function minimizes total costs (wages, overtime, hiring, layoffs, inventory holding).  
- Constraints ensure demand satisfaction, workforce balance, and feasible monthly operations.

✅ **Excel Solver Implementation**  
- Structured implementation to determine monthly staffing and production levels that meet demand.  
- Sensitivity analysis reveals shadow prices and marginal values for workforce and production constraints.

✅ **Managerial Insights & Recommendations**  
- **Workforce Stability:** Workforce changes have the biggest impact on costs; maintaining a stable team is crucial.  
- **Overtime Minimization:** Overtime production is costlier than standard production—limiting it is key.  
- **Hiring/Layoffs:** Minimize layoffs due to high associated costs, and focus on workforce optimization.  
- **Boost Productivity:** Higher productivity per worker reduces the need for overtime and workforce fluctuations.  
- **Inventory Management:** Holding inventory has minimal impact compared to workforce-related costs.

---

## 📊 Key Results & Takeaways

- Achieved **total minimized cost: $44,088.8** over six months.  
- Workforce fluctuated only as needed, balancing cost efficiency and demand fulfillment.  
- Shadow prices indicate layoffs are costly (up to **$480.75**) and should be avoided whenever possible.  
- Strategy focuses on leveraging existing workforce capacity and strategic hiring to maintain operational stability.

---
