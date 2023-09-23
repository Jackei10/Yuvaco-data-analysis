# Yuvaco-data-analysis
Problem statement: 

Please consider yourself working as a data analyst at a firm that deals with the delivery of goods and packages. They have their database through which they calculate the cost of expedition for each package which represents a single row in the data. 

Task - Write a Python script that calculates the same - i.e. cost of each package delivery in the dataset. The cost grid to calculate the cost is provided as well.  

Sample Data: 
Package ID	Weight (kg)	Distance (km)	Delivery Type
1	3	10	Express
2	5	25	Standard
3	2	5	Express
4	6	15	Standard
5	4	30	Express

Cost grid: 

cost_grid = {
    'Express': {
        'Base Cost': 10,
        'Cost per kg': 2,
        'Cost per km': 1,
    },
    'Standard': {
        'Base Cost': 5,
        'Cost per kg': 1.5,
        'Cost per km': 0.5,
    }
}
