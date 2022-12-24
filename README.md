# River_scenario
It is an Computer Graphics project. Made using OpenGl and Python

In the project "River Scenario" we implemented Midpoint Line Algorithms, Midpoint Circle Algorithm, Transformations matrixes (Rotation, Scale, Translation) and different open gl functions for quads, triangles, points etc. Let's demonstrate for each part.

1. For background sky & river part we used Quads with gradient color. Assigned different colors before calling each point for gradient colors.

2. For Sun we used Midpoint Circle algorithm to draw & defined the point with rotation matrix. Where for different time from 5-19  we will have different value of theta & sun will be drawn.  

3. For trees we took a ideal triangle value. Then inside loop we scaled & translated the values with scaling & translation matrix. Also, for tree trunk we used Midpoint line algorithms.  

4. For Buildings we used Midpoint Line algorithm. We drew the buildings line by line inside loop & changed r,g,b for gradient color shade. 

5. For cloud we used two types white color & dark color where we used 3 circles together & places them with random.uniform limitation points.

6. For boat we took user inputted x value & take that as variable & drew different design with MPL, MPC, Quads respect to the point. 

So, we can change the Sun position with time input. Change the weather as cloudy/sunny & can define raining or not. Also, can move the boat as we want.
