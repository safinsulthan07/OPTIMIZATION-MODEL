# OPTIMIZATION-MODEL

"COMPANY": CODETECH IT SOLUTIONS

"NAME": Narasapuram Safin Sulthan

"INTERN ID": CT06DF620

"DOMAIN": DATA SCIENCE

"DURATION": 6 WEEKS

"MENTOR": NEELA SANTOSH

Optimizing delivery operations is a crucial task in logistics, where cost-efficiency and timely delivery directly impact a company’s bottom line. This project focuses on using Linear Programming (LP) to solve a delivery routing problem where goods must be sent from a central warehouse to three cities—A, B, and C. Each city has a fixed demand for goods and a distinct cost per unit of delivery. The ultimate goal is to determine how many units to deliver to each city in order to minimize the total delivery cost, while fully meeting the demand in all three locations.

The problem scenario is as follows: City A requires 30 units with a cost of ₹4 per unit, City B needs 50 units at ₹6 per unit, and City C demands 20 units at ₹8 per unit. The total number of units that must be delivered is 100. Although delivery trucks have a capacity of 40 units per trip, we assume for this model that an unlimited number of trucks are available, so capacity is not a limiting constraint. This simplifies the problem, allowing us to focus solely on minimizing the overall cost based on the number of units sent to each destination.

To solve this optimization problem, we use Linear Programming, a powerful mathematical technique for decision-making in constrained environments. The key components of our LP model are the decision variables, objective function, and constraints. The decision variables (xA, xB, xC) represent the number of units delivered to each city. The objective function seeks to minimize the total cost, calculated as 4xA + 6xB + 8xC. The constraints ensure that each city receives the exact quantity it requires: xA = 30, xB = 50, and xC = 20. Additionally, non-negativity constraints ensure that no city receives a negative number of units.

The problem is modeled and solved using Python’s PuLP library, which provides a user-friendly way to define LP problems. The model is set up with the objective and constraints, and then solved using the library’s built-in solver. The code outputs both the status of the solution and the number of units allocated to each city, along with the minimized delivery cost.

The output confirms that the solution is optimal, with exactly 30 units sent to City A, 50 to City B, and 20 to City C—matching the demand precisely. The total delivery cost comes out to ₹580, which is the minimum possible under the given constraints. This demonstrates that the LP model has effectively achieved its goal of cost minimization while fulfilling all demands.

In conclusion, this project showcases how linear programming can be used to solve real-world logistics problems efficiently. Even in this simplified scenario, LP proves to be a valuable tool for decision-making in distribution and transportation. The model can easily be extended to include more complex constraints, such as limited truck availability, delivery time windows, or varying route capacities, to better reflect real-world challenges. This foundational example lays the groundwork for more advanced optimization strategies in logistics and supply chain management.

<img width="1427" height="258" alt="Image" src="https://github.com/user-attachments/assets/5e549665-d998-4f65-9eb0-01ff4ef2fc9c" />
