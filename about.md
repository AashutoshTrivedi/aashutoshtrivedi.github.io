---
layout: page
title: About
permalink: /about/
---
<!-- ![alt text](images/author.jpg) -->
<img align ="center" src = "/images/author.jpg">

> ###*“Wisdom is not a product of schooling but of the lifelong attempt to acquire it.”*
> *– Albert Einstein*

Bonjour! Namaste! Hello!
Myself Aashtosh Trivedi, a Mechanical engineering graduate form [IIT Jammu](iitjammu.ac.in).

I had been the general secretary of students body, and been an integral part of the baja team. Apart from it I'm deeply passionate about the new technology and its impact on tranforming the society. I have a my interests in the field of machine learning and cloud based computing.

Coming on the internships, I interrned with jugaad analytics which is an analytical firm located in Amsterdam which works in the field of predictive maintenance , big data analytics and Stock market prediction.

I created an end to end system for analysing the dataset for Hinekein beers. This was implemented using OSEMN(obtain, scrub, explore, model, interpret) structure. The dataset was extremely dirty, so first task was to develop a generic class to clean the dataset. The constructor for this class takes a table as an input, and takes appropriate decisions and removes the unnecessary information including redundant columns, checks for missing values, and then aggregating the data by dates.

Next element was to do visualization and descriptive statistics from the datasets to gain insight from the data. For that I used python matplotlib and seaborn in case of visualization and for stats, used statsmodel and scikit-learn library.
This gave me an idea of the basic statistic entities along with hiw the tablular valies are coorelated with each other and what type of ML model can be deployed for the situation.
Now there were columns which showed the quantity of beers sold for different time period. Next task was to create a forecasting model to predict the approximate sales in the coming time on daily, monthly and yearly basis. For that I integrated two models initially namely ARIMA and SARIMA models which stands for autoregressive integrated moving average models. In case of time series, the basic assumption of independence of data is voilated. So for that we have to use slightly different models than the convention ML models.
So training the model using Arima and sarima with different parameters and comparing the results I forecasted the values for the next dates on monthly and weekly basis.

Rest of the internships were in mechanical domain, so I'll skip those. Moving on to the major projects and courses that I have done in field of cs.
I took a computer vision course as an elective here in the college where I learned about different types of filters, morphological operations, feature extraction and detection techniques, homography matrices and 3d reconstruction. I am certified for ML by andrew ng on coursera, deep learning on coursera and data science with python. I also have through understand of cloud computing domains including AWS and GCP which I have explored in few of my projects.

I also have an basic understanding of different architectural styles persay monolith architecture, the problems associated with it and microservices architecture. I have few projects that included the use of docker and kubernetes, basically it was a web based application, which I'll come a little later and then an understanding of the various domains in big data. In particular I have done Hadoop cluster setup and written a element counting algorithm in map reduce paradigm for thsi purpose.

So now coming on to the projects, I'll just focus on few relevant projects.
First project is dog breed classification API running on GCP, it's a rest api service which runs on a server using flask in python. In order to accomplish that, I created a GCP envirnoment. On that deep learning model was created using keras flask and docker which served as rest api. I uploaded the container into dockerhub, created a kubernetes instance on the GCP and deployed the dockers on it, so i have multiple servers. Using docker and kubernetes enables low latency, scalability and fault tolerance.
Talking a little bit about dockers, docker is one of the best containerisation technology present today. Container basically are like virtual machines but they are different in the sense that they all share same the kernel as the operating system unlike virtual machines. Virtual machines tend to directly connect to the hardware using hypervisor but in containers they interact with os kernel with their indepent dependencies and files. I can basically run and deploy any software in docker. Now coming to kubernetes, it's an orchestration platform for running containers. In kubernetes, we have a master kubelet and other nodes where kubeltes are installed. On thes, docker image is installed and a yaml directive is wrutten to describe the architecture of the kubernete cluster.

Currently also I am working on a project based on object detection and IOT. Basically it's a cap for blind people. So in this I will have a cap with 6-8 cameras around and it will reconstruct a 3-d world and detect an object, once detected it will measure the distance of the object with the user, and then output an audio file stating that object x is at a distance y in this particular direction. Although this is quite a big project but, we are thinking of patenting this. Till now, what we have accomplished is taking the input of two cameras using ov7673 module and two Arduinos, which we will shift to raspberry pi, and using the video which is generated at 30 fps, we will create a opencv program for 3d reconstruction of the video using kafka and spark, and then do object detection on it. Once the object is detected, we'll determine the distance of the object, as I'm having two cameras that can easily be possible. I will convert this into a voice file and with direction we'll send the signal to the audio output to user. So this is the workflow of the project. It's certainly an ambitious project an d we'll start it and make a smaller prototype and later our junior batches may carry forward it.

Yes sir, I would like to add one more thing. I may not be expert or much experienced in computer science field but I certainly am passionate about this field which can be easily seen through my previous projects. Apart from this I am hardworking, dedicated and a responsible person. This can be verified through my resume. I had been house secretary in my first year of college, elected by students. Based on my work, dedication, sincerity, I was again elected by students for position of general secretary Student's council. In the third year I had been selected by faculties as an Marketing and operations head of our team kinesis which developed car from scratch. And I have organised many fests in the college. This shows my wide aoura and capabilities as well as it tells that whatever work I am assigned to, I do it with complete dedication and commitment.
If given opportunity I can be a great asset to the company.
