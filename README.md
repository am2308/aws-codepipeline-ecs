# aws-codepipeline-ecs

AWS Project - CI CD Pipeline to AWS ECS for Docker App + CodeCommit + CodeBuild + CodeDeploy
Here's the [YouTube Video](https://youtu.be/knFabwOn1JE).


## Installation

Follow next steps in order to install nodejs app and create a dockerimage

### Step 1 - Git clone 

```
git clone https://github.com/am2308/aws-codepipeline-ecs.git
```

```
cd aws-codepipeline-ecs
```

```
git checkout aws-codepipeline-ecs
```

### Step 2 - Build and run docker container

```
docker build -t aws-codepipeline-ecs .
```

```
docker run -dp 3000:3000 aws-codepipeline-ecs
```
  

