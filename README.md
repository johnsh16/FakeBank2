# FakeBank2

This project is part of my curriculum with the MIT Full-Stack Engineering certification. It is an extension of the previous FakeBank project, which now inlcudes database connectivity. (If you are trying to run this project locally, I suggest spinning up a MongoDB instance in a docker container with a port at 27017. You could also refactor the code to connect to a Mongo URI.)

You can clone this repo - run "$npm install", then "$node index.js". If there is a Mongo instance running at 27017, everything will work according to plan. 

![Screen Shot 2022-01-31 at 7 39 59 PM](https://user-images.githubusercontent.com/84100060/151898058-d787b5dc-a277-4f18-a0c3-d13902f1aff5.png)

Technologies used in this project: React.js (front-end), Bootstrap (front-end styles), Node.js (server), MongoDB (client running on Node). 

The project features the ability to create accounts which persist over time, using MongoDB as well as React context to share data over the app. 

MIT License
