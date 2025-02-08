# OPTIMIZATION_MODEL

COMPANY:CODTECH IT SOLUTIONS

NAME:SATHYA DHARSHINI G

INTERN:CT08KFM

DOMAIN:DATA SCIENCE

DURATION:4 WEEKS

MENTOR:NEELA SANTHOSH

DESCRIPTION OF THE TASK :

The code uses **PuLP**, a Python library for linear programming, to determine the optimal number of units of **Product X and Y** to produce while maximizing leftover stock. It first defines **X and Y** as decision variables, representing the number of units produced, ensuring they are continuous and non-negative. The objective function is set to **maximize the total leftover stock**, represented by the equation **(X + Y - 50)**, which accounts for initial stock and demand fulfillment. The goal is to ensure that after production and sales, the company retains as much stock as possible while using available machine time efficiently.  

Several constraints are added to ensure feasibility and resource limitations. The first constraint limits the total processing time on **Machine A** to **40 hours (2400 minutes)**, while the second ensures that **Machine B** does not exceed **35 hours (2100 minutes)**. These constraints ensure that production stays within the available machine capacity and prevents exceeding operational limits. Additionally, demand constraints require at least **45 units of X** and **5 units of Y** to be produced to meet customer requirements. This guarantees that customer demand is satisfied while preventing stock shortages.  

After defining these constraints, the model is solved using `solve()`, which finds the optimal production levels for **X and Y** while ensuring efficiency and feasibility. The results are then printed, showing that **45 units of X and 6.25 units of Y** should be produced to **maximize leftover stock**, which results in **1.25 units** of stock remaining at the end of the week. This outcome ensures that the company optimally utilizes machine time while fulfilling demand. The solution also helps in planning production schedules efficiently, minimizing resource wastage, and ensuring smooth operations. This approach ensures **optimal resource utilization, demand fulfillment, and efficiency** in production while working within machine time constraints.
