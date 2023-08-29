# MDP REPRESENTATION

# AIM:
### To represent any one real-world problem in MDP form.

# PROBLEM STATEMENT:
### To develop a snake game application.The role of the agent is to promote if the level is cleared by eating a food or depromote if the snake game is lose.

# Problem Description
### If the level is cleared by eating a food or depromote if the snake game is lose.

# State Space
### {L1,L2,L3}--->{0,1,2}
### L1--->level 1
### L2--->level 2
### L3--->level 3

# Sample State
### L1--->0--->level 1

# Action Space
### {W,L}--->{0,1}
### W--> Winning by eating food
### L--->lossing by not eaten food

# Sample Action
### W--->0--->Winning

# Reward Function
### {+1, if we come closure to winning
### {+0, otherwise

# Graphical Representation
![Screenshot (17)](https://github.com/DHARSHINISENTHILKUMAR/mdp-representation/assets/113699377/82e8dde9-368e-43fa-8170-7a8857b03c4d)


# PYTHON REPRESENTATION:
~~~
P = {
    0:{
        0: [(0,1,1,True)],
        1: [(1.0,0,1.0,False)]
    },
    1:{
        0: [(0,2,1,True)],
        1: [(1,0,1,False)]
    },
    2:{
        0: [(0,2,1,True)],
        1: [(1,1,1,False)]
    }
}

~~~
# OUTPUT:
![image](https://github.com/DHARSHINISENTHILKUMAR/mdp-representation/assets/113699377/a157c68f-9ced-4f20-8827-d3faffa59c78)



# RESULT:
Thus the given real world problem is successfully represented in a MDP form 

