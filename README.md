# Cyclistic-Bike-Sharing
This Case Study was done as a requirement for the Google Data Analytics Certificate. As part of this Capstone Project, I had to share it online.

In this case study, I used real data from a Bike Sharing Service from Chicago, though the name Cyclistic is fictional. I evaluated how different types of users engage with the service, determining trends and theorizing what was causing them. I was then able to develop an action plan based on those findings.

The easiest way to visualize this project is by downloading the Cyclistic.html and opening it on your browser.

If by any chance you want to run this code, you might have to adjust file paths, and/or put your data in a different directory.

**Requirements:**

* R and R Studio
* You might need to install some additional libraries, they are noted on the R Markdown file.
* Download the .csv (https://divvy-tripdata.s3.amazonaws.com/index.html) files from August 2021 to July 2022.
* Download the Cyclistic.Rmd

The goal of this case study was to find the differences between Casual and Member users in the last 12 months (August 2021 to July 2022). A Casual is defined as someone that bought a single ride or daily pass, while a Member is an individual that bought a yearly subscription.

**Here's a preview of the findings:**

First we looked at the raw number of rides:

![Number of Individual Rides](https://user-images.githubusercontent.com/16500908/189518623-22744e33-cae8-44c3-a996-8118b603e513.png)

It's clear who uses the service more. Or is it?

![Total Ride Time (in hours)](https://user-images.githubusercontent.com/16500908/189518657-b596d016-8ff5-44f4-9227-5fbc7ae33aa5.png)

Even though Members have more individual rides, Casuals come out ahead on total ride time. Why?

![Avarage Ride Time](https://user-images.githubusercontent.com/16500908/189518755-9660414a-a6d4-43f4-81c2-26c699dc77e9.png)

Casuals average ride time is significantly higher than members, and that's how they bridge this gap.

Another difference lies in when they mostly use the service:

![Number of Rides by Day of the Week](https://user-images.githubusercontent.com/16500908/189518787-7c1289a1-eb7d-48d2-822d-f47fddac980d.png)

Casuals ride more on the weekends, while members are better spread, but use the service more on workdays. This is most likely due to Members using the service to commute and for daily activities, while Casuals tend to ride for leisure. This is further supported by the seasonal data:

![Number of Rides per Season](https://user-images.githubusercontent.com/16500908/189518888-0142aadd-3ba6-4855-b54d-9ec84229ed00.png)

Member rides peak in Spring rather than Summer, like it is for Casuals, likely because they have free time from work and might even be on vacation outside of the city, therefore not driving so often.

In this chart, it is also interesting to notice how the number of rides drops from its peak for each group: Casuals by about 80% and Members by around 60%. We can visualize this easier on the following charts. First for casuals:

![Number of Casual Rides per Season](https://user-images.githubusercontent.com/16500908/189519108-49253089-6d31-45a8-a223-c4d74766b8f1.png)

And then for Members:

![Number of Member Rides per Season](https://user-images.githubusercontent.com/16500908/189519129-3298bb59-6ebc-4124-bef0-d0ba2b5618ae.png)

We can see that Member rides are better distributed throughout the year, making the service's revenue more stable and less spiky. 

The business goal for this analysis is to sell more yearly subscriptions, by turning Casuals into Members because the latter group is more profitable. **To help achieve this, we recommended 3 steps:**

1. Survey users to make sure that the assumptions based on this analysis are correct, to better understand why members decided to buy a subscription, and in turn to ask Casuals what would make them buy one.
2. Stimulate casuals to adopt bikes as their daily commute method. Showcase the benefits of bike riding for their general health.
3. Spread marketing material based on the days and regions where Casuals use the service the most.
