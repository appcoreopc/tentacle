# tentacle

Centralized package distribution.

This is a project to help manage package distribution in a deployment environment. 

In a microservice architecture, packages are oftend distributed and could potentially change. Imagine your dev rollout a new package and you need that to be part of your codebase. 
Your pain point now is to figure out, do you want to redeploy everything. 

This gives you the option to deploy those library to your environment without trigger the entire build pipeline.

Cient side download package and update the central repository. 

Server keeps track of packages that are distributed to give user visibiliy of their environments.

