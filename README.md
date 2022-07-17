# Docker_Final_Task


### About ###
Create a Python Web APP using FLASK that:
● Presents the Current BitCoin Price (LIVE)
● Stores the price in a Redis Database
● Presents the Average Price for the last 10 minutes (LIVE)

## Run localy ###

**First,** cloning the repository to your machine:
```bash
git clone https://github.com/nadeemjazmawe/Docker_Final_Task.git
```

**Second,** getting into the project directory
```bash
cd Docker_Final_Task/
```

**Finally,** runing docker compose :
```bash
docker-compose up
```
* if you run over linux OS(like ubuntu) you need to run:
```bash
docker-compose up
```

And you can enjoy the Web on:
``` 
http://127.0.0.1:5000
```

![image](https://user-images.githubusercontent.com/44744877/179414350-a3bdf64d-2011-43d2-8694-5f61189b453e.png)


### Run Dockerhub ###
**Also,** you can run the image from DockerHub, by this steps:
```
docker pull nadeemjazmawe/bitcoin-price
docker run -p 5000:5000 -d nadeemjazmawe/bitcoin-price
```


##Enjoy <3 ##
