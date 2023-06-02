# Burnout-Rate-Prediction-Heroku-Project

**Case Study**

Happy and healthy employees are undoubtedly more efficient at work. They assist the company to thrive. However, the scenario in most of the companies has changed with the pandemic. Since work from home, over 69% of the employees have been showing burnout symptoms (survey source: Monster). The burnout rate is indeed alarming. Many companies are taking steps to ensure their employees stay mentally healthy. As a solution to this, we’ll build a web app that can be used by companies to monitor the burnout of their employees. Also, the employees themselves can use it to keep a check on their burnout rate (no time to assess the mental health in the fast work-life 😔).

**Dataset**

* Employee ID: The unique ID allocated by the company to each employee.
* Date of Joining: The date when the employee had joined the company.
* Gender: The gender of the employee.
* Company Type: The type of company where the employee is working in (Service/Product).
* WFH Setup Available: If the work from the home facility is available for the employee (Yes/No).
* Designation: The designation of the employee in his/her organization. In range – [0.0, 5.0], 0.0 is the lowest designation and 5.0 is the highest.
* Resource Allocation: The number of resources allocated to the employee to work, to be interpreted as the number of working hours. In range – [1.0, 10.0] (higher means more resources).
* Mental Fatigue Score: How much mentally tired is the employee in the working hours in the range – [0.0, 10.0] where 0.0 means no fatigue and 10.0 means completely fatigue.
* Burn Rate: The target value in the data of each employee telling the rate of burnout during working hours in the range – [0.0, 1.0] where the higher the value is more is the burnout.
