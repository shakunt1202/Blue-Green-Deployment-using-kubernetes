# Blue-Green-Deployment-using-kubernetes
The gist of blue-green deployments is to have two identical environments, conventionally called blue and green, to do continuous, risk-free updates. This way, users access one while the other receives updates.


![Blue-Green Deployment](https://user-images.githubusercontent.com/59165595/193416705-9d5ebcb1-cff2-4af0-85ea-6b215e7fa795.jpg)

Blue and green take turns. On each cycle, we deploy new versions into the idle environment, test them, and finally switch routes so all users can start using it. With this method, we get three benefits:

We test in a real production environment.
Users don’t experience any downtime.
We can rollback in an instant in case there is trouble.
