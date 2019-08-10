# Shopping mall data analysis:speech_balloon:

## :star:Project description:star:

 This project is designed to analyse data of the behaviors' of online shopping mall users. 
 
## Data description

The data,formed of 12330 rows and 18 columns was reduced into: Bounce Rates, Special day, Month, Browser, Visitor types.

## Before the graphs

#### Aim
To figure out what factors affect an online shopper’s site visit frequency
#### Factors
 Month, Special day, , and if the user have visited before 
#### Explanation (Factors without the need of explanation are left without)
* Special day- days such as Halloween, Christmas, Valentine’s day, etc.
* Bounce rate- total one-page visits/total entrance visits 

#### Hypotheses
* Days nearing special days will show less bounce rate
* If the user has visited before, they will show higher bounce rate than new visitors
* Winter and summer months will have higher bounce rates
* There will be a difference in bounce rate within different browsers
## Results + Analysis
### Factors of bounce rates
![](/img/BounceRateFactor_full.PNG)

#### Browser
![](/img/BounceRateFactor_browser.PNG) 

In the graph, it can be clearly seen that browsers 1+4 have the most bounce rate and 8 with the least. As a clear fluctuation among the browser's bounce rate can be seen, it may say that the hypothesis about the browser written above-There will be a difference in bounce rate within different browsers- is true. 

#### Visitor type
![](/img/BounceRateFactor_visitorType.PNG)

It can be seen quite certain that there is a major difference between the visitor types and their bounce rate. Returning visitors show higher bounce rates, hence proving the hypothesis about visitor types true. It also shows that visitor type may be a factor that differ bounce rates. 

#### Month
![](/img/BounceRateFactor_Month.PNG)

The graph shows the bounce rate fluctuating on months. With the exception of two months without data, it can be noted that July and February has the lowest bounce rates, despite the hypothesis that winter and summer months will have higher bounce rates. This could probably be because more items are bought in preparation of the upcoming, or ongoing harsh weather.

#### Special Day
![](/img/BounceRateFactor_SpecialDay.PNG)
The graph does show the bounce rate getting lower when approximating the special day, but it also shows the bounce rate increasing until value 0.8. 
The fact that the bounce rate got lower in value 1.0 implies a behavior of online shoppers that it is likely for them to delay the purchase until the final day.

### Special Day bounce rate relationship with new and returning users

![](/img/rkddlwns_tot)

#### New users' maximum
![](/img/rkddlwns_nwmx)

Shows that new visitors tend to have more interest on the value 0.2, 0.4, and lose interest quickly on the first day (value 0)
#### Returning users' maximum
![](/img/rkddlsnws_rvmx)

Returning users generally lose interest quickly on special days
#### New users' average
![](/img/rkddlwns_nwavg)
Actually, it was only some that lost interest quickly on the first day- most were interested about the online shopping mall
#### Returning users' average
![](/img/rkddlwns_rvavg)

Huge difference between maximum and average value shows that only some of the returning visitors left the site quickly without interest, but the majority were interested.
#### So...

Less bounce rates int new users than returning users show that while the site manages the capture the customer's eye and interest at first, the site fails to catch returning visitor's attention and customers eventually start to lose interest.

