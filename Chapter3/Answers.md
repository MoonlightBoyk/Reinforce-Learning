Ex3.1

The carnot engine: how to achieve the maximum efficiency of converting heat from two huge reservoirs in different but constant temperatures into work with some ideal gases?
states: Volume and Pressure of the ideal gas PV=RT  
rewrads: the ratio of the heat converted to useful work after completing a cycle  
actions: isothermal expansion or contraction under high or low temperature, adiabatic expansion or compression, isobaric processes  

Learning english: how to learn english well? The actions need to accumulate to stimulate an essential rise of your english level. So the process is nonMarkov. And the states and rewards could use the same thing.  
states: TOEFL score  
rewards: TOEFL score  
actions: read, listen, speak, write with materials on differnet levels or do nothing  

Dating with girls: How to win her hearts by a series of acitvities.  
states: My and her free time, My pocket money, relationship with the girl: unknown, acquainted, familiar, close or Girlfriend, her emotions: happy, sad, calm, angry, worried and other various subjective emotional states  
rewards: kiss +10,  hand in hand +5, smile +1, nice guy -1, smack -5  
actions: study together, chat, take a lunch, watch a movie, go to an amusement park, travel, send a gift  
Indeed, I hope so.

Ex3.2

It is hard for me to think of a case in point. If you couldn't get any response from the environment or the response couldn't be used to determine whether the actions is good or not, it would be quite hard to achieve the goal.

Ex3.3

I think the line between the agent and environment depends on the specific circumstance. When we are learning how to drive, we should focus on the accelerators, brake and so on. Neither want we want to go or the torque from the rubber counts. For a car racer, the tire torque really matter since it counld influence the speed of the car greatly. And for veteran drivers, they konw their car very well and are unnecessary to worry about the detailed acceleration and brake since driving has been something like instant for them. So, say if they want to save the petrol, they should decide the route for the day.  
I think these locations vary in trems of the abstract level. The brain decision is more abstract than the body meeting the machine since there are many other ways to reach the location like the public transit. And there are many different combinations of acceleration and brake to exert the same tire torque on the road. These locations should match the abstract level we concern I think.

Ex3.4

The ruturn wuold be ![Ex3.4](Ex3.4.svg) , k is the number of time steps before failure. But the continuing formulation will contain other episodes and the k on the exponent in future episodes would take the time step in the former episodes into account. I am confused. Since the rewards would be given after each episode. Why there is a reward associated with each time step in the episodic view?   

Ex3.5

I don't think I have given the effective info to the agent. Maximize the return doesn't necessarily mean the ability to pass the maze. Say if the maze is simple enough, it will always find a way out by random trials. So the agent gets the reward every time and doesn't need to make any change. It would keep trying randomly and thus show no evidence of learning.

Ex3.6

After seeing the first scene, I, the vision system, don't catch the Markov state of the environment. Say if the sun lies behind me and I couldn't see it, I'm unable to predict the changes of the light, caused by the rise of the Sun, on the objects I see. Otherwise, if the state is Markov, it's a pretty nice thing since we could just catch a sight of the universe and know all about it. On the other hand, the complete darkness from the broken camera is a Markov state. I know I'm going to spend the day in the endless and frightening darkness. 

Ex3.7

![Ex3.7](Ex3.7.svg)

Ex3.8

From the account of the problem, we know ![3.8.1](Ex3.8.1.svg) for all four directions and r=0. So ![3.8.2](Ex3.8.2.svg). The Bellman equation holds for the center state.


Ex3.9

![Ex3.9](Ex3.9.svg)

Ex3.10

It may make a big difference. Say if the agent get an reward -1 every time step in the maze like the case in section 3.2, the agent would then try to minize the time in the maze to maximaize the rewards. When we add 2 to all the rewards in one episode, the agent would spend as much time as it can in the maze since the reward for each time step are positive now. In this case, the sign of the rewards matter rather than the relative values of different states in Ex3.9.

Ex3.11

![Ex3.11](Ex3.11.svg)

Ex3.12

![Ex3.12](Ex3.12.svg)

Ex3.13

We could reach the hole within one shot on the green. So the green forms the -1 contour. If we have two strokes, we could first play with the driver and then the putter to reach the possily farest boundry of the -2 counter like the -2 boundary in Fig 3.6 below. In the -2 counter shown in Fig3.6 above, we could either use the putter or the driver. Now we have three strokes, we could include the tee now with another stoke by the driver. So the -3 contout would assemble the -3conuter in Fig3.6 below.

Ex3.14

With a stroke of the putter, we could reach the hole on the green, so the green area composes the -1 region. Since the putter is more accurate, the second counter we will use the putter as well. The -2 counter is that in Fig3.6 above. If we have three strkes, we would use the driver in the middle step to go as far as possible. So -3 counter looks like the -5 one in Fig 3.6 above. But the boundary doesn't locate behind the tee. We need another stroke of the driver to expand the region with expected return -4.

Ex3.15

![Ex3.15](Ex3.15.svg)

Ex3.16

According to the best policy, the agent should move directly towards A from A'. Since there is no rewards along the way, after four upward actions, we get ![Ex3.16](Ex3.16.svg) is the Bellman optimality equation for the site A. So the optimal value of the best state is 24.419.
