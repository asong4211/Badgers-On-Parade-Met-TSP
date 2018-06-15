# Badgers-On-Parade-Met-TSP

![Badgers on Parade]("./badgers.png")

Recently, my school (University of Wisconsin-Madison) installed multiple badgers statues across the campus as a public art event. All the statues are spread across the campus and downtown Madison area, as well as some outside of the downtown Madison area.

I am interested in finding a route to visit all of the badger statues. This problem can be formulated as a travel salesman problem (TSP), where I will start at one of the statue, and tour all of the statues, and come back to where I started. However, the TSP problem is known to be NP-Hard, where solving them would take n! time complexity. In this case, there is a total of 54 statues, which would take about $ 2 \times 10^{71} $, or about 15 days to just find the optimal solution. In this project, I try to solve this problem by using two of the most popular relaxation method for TSP: Subtour Elimination method and Miller-Tucker-Zemlin formulation.

