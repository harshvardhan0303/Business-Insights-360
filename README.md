# Business Insights for a computer hardware selling company.

## Problem Statement
AtliQ Hardware is a computer hardware selling company, whose business is in India and many more countries. The manager wants to know about the sales, stock present and many more insights but he has to look over too much excel files to get these insights. He want a visual report which help him in taking decisions regrading his business and regularly update of that let him know what is the current situation, also he wants to know the supply chain view so that he can efficiently move forward with his business.

## Solution Approach
I have been provided with two big sql files and many excel files(in src folder) to help me in creating this report. After that I have asked the relevant questions what basically the manager sir wants, the final outcome i received is that he wants a visual report wich not only for him but also for the other members of organization, like if they are from sales department they can see the sales view, if they are from supply chain then they have a look over it and same for marketing team as well. Manager sir is more interested in seeing the finance view. So, basically we need to cover up all the sectors of the organization. 

All started with checking the data using SQL. In this check, I have observed many error related to blank data, negative value of prices etc. So, after loading the data in Power BI I have removed those errors using Power Query Editor. Once the data is cleaned I have started creating measures based on the requiremnets of the company and the manager. After creating the relevant measures, I moved on with creating different dashboards and combining all of them. The first I have created the Finance View, then Sales View, Marketing View, then Supply Chain View and Executive View. After that I have ended up by creating the tool tips for more clear visualisation and then Home page and Support page through which on clicking on dedicated icon you can reach to each particular dashboard of the report. Then on the instructions from the manager I have also deployed it on Power BI services.  

## Tech Stack
Visualisation: Power BI

Dependencies: MS Excel , SQL queries for checking the errors present in the raw data and cross checking the measures. 

Performance Metrics: MS Excel , MySQL , DAX and M language, Measures in Power BI.

## Project Architecture

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/ec1ac792-4c0c-48ae-99d8-31590e578db0)

## Results

Here, I am going to attach all the dashboards combinly, which I have created for diffrent departments of AtliQ Hardware. The order for the same is wriiten is -

## Home Page - 

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/ccd687e2-075a-42d6-9089-c3c00ec20fa1)

## Finance View -

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/d85625a9-571b-4f38-93ac-3db794d53279)

## Sales View - 

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/48e432f5-6e1a-4350-8619-9e5e66401496)

## Marketing View -

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/e113024c-58ba-4c52-a308-927d67039a24)

## Supply Chain View -

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/db924f97-f562-4f33-8b55-638c6d6ab318)

## Executive View -

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/d4d0dead-4d77-419d-886c-b8b819187ccc)

## Info Page

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/66cd3909-0301-4eb0-9367-81812d63fd8d)

## Support

![image](https://github.com/harshvardhan0303/Business-Insights-360/assets/91109131/d294e8ba-635c-4d92-8b1c-dda561c53cc7)


After creating all these dashboards for different sectors of the organizations, with the permission of the organization I have deployed it on Power BI services, so that with the more addition in data there is no need to make this report again, it will automatic update after refreshing the data.

