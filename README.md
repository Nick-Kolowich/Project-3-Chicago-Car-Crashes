![png](https://raw.githubusercontent.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/main/Images/coverphoto.png)

## Outline

This project examines the causes of traffic accidents within the city limits of Chicago. Approximately 60,000 accidents occur each year in Chicago, many of which are due to driver negligence. The Chicago Traffic Management Authority (TMA) could use this analysis to implement policies which would potentially reduce the number of accidents that occur annually.  

## Links

[Presentation](presentation.pdf)<br/>
[Purpose](README.md#Purpose) <br/>
[Data Description](README.md#Data-Description) <br/>
[Map of Accidents](README.md#Map-of-Accidents-in-Chicago-by-Cause) <br/>
[Questions](README.md#Questions) <br/>
[Summary](README.md#Summary) <br/>

## Purpose
To build a model that will predict accident causality based on factors such as weather, speed limit, and lighting conditions.

## Data Description

Crash data shows information about each traffic crash on city streets within the City of Chicago limits and under the jurisdiction of Chicago Police Department (CPD). The data contains information on 453,326 accidents occuring inside the Chicago City limits between 2015 and 2021. All crashes are recorded as per the format specified in the Traffic Crash Report, SR1050, of the Illinois Department of Transportation. <br/>

## Map of Accidents in Chicago by Cause
<details>

  <summary> Legend </summary>
    
![imglegend](https://github.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/blob/main/Images/legend.png)

</details>

![img](https://github.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/blob/main/Images/chicagomap.png)

## Questions
    
<h3> Question 1: What time of day do crashes typically occur? </h3>
<details>
    
   <summary> Spikes in accidents are primarily seen during commuting hours. </summary>
    
![image png](https://github.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/blob/main/Images/hourofcrashdistpresentation.png) 

</details>

<h3> Question 2: Does inclement weather disproportionately cause fatal accidents? </h3>
<details>
    
   <summary> Weather conditions have little bearing on accident fatality. </summary><br/>
   
   <ul>
   <li> Rain is 1.08x more likely to be present during a fatal crash. </li>
   <li> Snow is 0.55x as likely to be present </li>
   <li> Fog/Smoke/Haze is 1.90x more likely </li>
   </ul><br/>
    
![image png](https://raw.githubusercontent.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/main/Images/weatherfatalvsnoinjury.png)

</details>

<h3> Question 3: How has Covid-19 impacted accident frequency in Chicago? </h3>
<details>
    
   <summary> Far fewer accidents have occurred after March 2020. </summary><br/>
   
   <ul>
   <li> 2018 </li>
    <ul>
    <li> 68,286 accidents</li>
    </ul>
   <li> 2019 </li>
    <ul>
        <li> 65,106 accidents </li>
    </ul>
   <li> 2020 </li>
    <ul>
        <li> 42,375 accidents </li>
    </ul>
   </ul><br/>
   
   The blue line denotes the stay-at-home orders issued by Governor Pritzker on March 20th. <br/>
   
![image png](https://github.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/blob/main/Images/covid19traffic.png) 

</details>

## Summary

Most of the accidents in Chicago are attributable to driver negligence, a broad category which encompasses things such as following too closely, failing to yield, improper turning, and many other traffic violations. The Chicago Traffic Management Authority (TMA) could potentially seek to reduce these occurrences by implementing harsher penalties for traffic violations. <br/>
 <br/>
There is a noticeable spike in accidents during commuting hours, both in the morning and evening. A potential solution to this might be to stagger business start times, to alleviate congestion on the roads during the mornings and evenings. For instance, the 8 hour work day could be shifted forward two hours for some businesses, starting at 11 and ending at 7, rather than the traditional 9-5. 
