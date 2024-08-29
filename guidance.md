# Guidance

Here is some guidance to this kata. 

There are many ways to test. We can test each unit of code separately, we can test entire functionalities starting from
where the user requests comes in up to the actual result, etc. 

Here, the point is that we learn to identify process, that we see which parts of that process are infrastructure and which
parts are more behaviour. 

In this kata, we focus on identifying the behaviour and writing tests for the behaviour. Everything is ridiculously simple, which 
makes this an excellent starting point to hone some testing and design skills. 

This exercise is calculator in webservice form. We right a controller to accept user requests and then we delegate these
requests to some other code units. The rest controller is considered to be infrastructure while the code units that will 
do the calculations are considered to be behaviour. 

The solution will be on the solution branch, the full implementation of everything will be on an implementation branch. 
Feel free to clone this project, create your own branch and try it out yourself. You can always verify with the solution
branch. 