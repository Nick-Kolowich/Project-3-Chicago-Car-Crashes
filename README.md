![png](https://raw.githubusercontent.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/main/Images/coverphoto.png)

###
Outline
Purpose
City of Chicago Map
Description of Data
Main Questions
Summary Conclusions and Insights
Future Work

### Purpose
To build a model that will predict the causality of an accident based on factors such as weather, speed limit, and lighting conditions.

### Map of Accidents in Chicago by Cause


### Data Description
<details>
    <summary> Expand </summary>
Crash data shows information about each traffic crash on city streets within the City of Chicago limits and under the jurisdiction of Chicago Police Department (CPD). The data contains information on 45,3326 accidents occuring inside the Chicago city limits during 2015. All crashes are recorded as per the format specified in the Traffic Crash Report, SR1050, of the Illinois Department of Transportation.
</details>

### Questions
    
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
    
![image png](https://github.com/Nick-Kolowich/Project-3-Chicago-Car-Crashes/blob/main/Images/weatherfatalvsnoinjury.png) 

</details>

<h3> Question 2: How has Covid-19 impacted accident frequency in Chicago? </h3>
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

