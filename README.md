# Examining the 'Carseats' dataset using Python

Using a lasso regression model in Python to measure the impact of different variables on sales:

<img width="1314" height="559" alt="carseats_lasso" src="https://github.com/user-attachments/assets/95ac71d5-179f-429d-b721-876786d55960" />

Optimal Alpha: 0.0040
Model R2 Score: 0.8897

--- Feature Impact (Coefficient Weights) ---

ShelveLoc_Good      1.930000

CompPrice           1.376535

ShelveLoc_Medium    1.002849

Advertising         0.836419

Income              0.421584

Urban_Yes           0.056942

Population          0.028840

Education          -0.054410

US_Yes             -0.133534

Age                -0.785822

Price              -2.238539

dtype: float64

A good shelf location has almost twice the impact in sales over a medium shelf location, and has more than twice the impact of the level of advertising.
