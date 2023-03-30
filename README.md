﻿# Dockerized Node App

<h3>1. Creating the docker Image</h3>

```docker build -t node-image .  ```

<h3>2. Running the above created Image via a Docker Container</h3>

```docker run -dp 3000:3000 node-image  ```

<h3>3. Now visit localhost:3000 to view the node app </h3>
