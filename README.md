# Trajectory-

I want to generate a speed-distance graph. In my case I have 3 phases: constant acceleration, constant velocity(cruising) and deceleration. 

![image](https://github.com/Oblivion9924/Trajectory-/assets/118735797/833fc863-5e5a-4851-a4f5-48bece06f830)

I tried to generate a plot with those 3 phases and I have attached a code used to calculate it in the commit. That looks like this:

![Figure_1111](https://github.com/Oblivion9924/Trajectory-/assets/118735797/63d01d98-7afe-4bb4-ab04-1def5294dcbe)
As you can see from the plot that it is calculating for just 0-1000 m. 
Expectation: I want to add different stops in between the whole journey. i.e., stops = [1000, 185, 425, 300, 300, 425, 185, 1000]  # Distances to stop in meters
             I want to generate this 3 phases between each stops. Their are 2 cases possible : 
1. If the intermediate distance is larger the train can achieve it's max speed so the constant acceleration, constant velocity(cruising) and deceleration will be calculated.
2. If the intermediate distance is smaller the train can't achieve it's max speed so the constant acceleration, and deceleration will be calculated.
             This is what I tried to generate:
             
![Figure_111](https://github.com/Oblivion9924/Trajectory-/assets/118735797/aa50cf38-4855-4ccd-a06b-d807ebc42deb)

             I tried to code it but their is some miscalculation or logic error. 
