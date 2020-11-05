# SSH-ECS
Simple cli tool to easily connect to any container on any AWS ECS cluster. With Github authentification to manage authorization

/!\ Still not finish, frequent updates

### Cli preview: 

<details>
<summary>See pictures</summary>

![Service list](images/service.png?raw=true "Service list")
![Container list](images/container.png?raw=true "Container list")
![Connection](images/ssh.png?raw=true "Connection")
</details>

### Temporary auth preview:

<details>
<summary>See pictures</summary>

![Ask](images/ask.png?raw=true "Ask")
![Wait](images/wait.png?raw=true "Wait")
![Slack](images/slack.png?raw=true "Slack")
</details>

##  What you need:

* A vault cluster with the OTP generation set up
* A single ec2 server (Or use docker in ecs) to host the server
* A github org to manage auth and access (Currently only github is supported, but i want to add Google auth too (plz do it for me :pray:) )

### Client

You can find the client documentation [here](https://github.com/antoiner77/ssh-ecs/tree/master/Client#ssh-ecs)

Best is to fork this repo and to distribute the client preconfigured (with the address of your server) to all your users

### Server 

You can find the server documentation [here](https://github.com/antoiner77/ssh-ecs/tree/master/Server#ssh-ecs-server)


###### Contributors

[vvanholl](https://github.com/vvanholl/)
