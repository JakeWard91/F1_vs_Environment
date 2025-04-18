# F1_vs_Environment
A project to see the correlation in how the environment impacts F1

## Table of Contents
* [Motivation](#Motivation)
* [Technologies](#Technologies)
* [Problems & Hurdles](#problems--hurdles)
  * [Getting the Data](#getting-the-Data)
  * [Data Normalization Trouble](#normalizing-the-data)
  * [Hurdles](#Hurdles)
* [Link to Dashboard](#link-to-dashboard)

## Motivation
#### For many years now, I have had a passion for F1. It would be a dream to be able to work in analytics for a team or organization within it. The analytics that go into a race and the amount of data that is created, sifted through, and used is immeasurable and astounding.

#### My project therefore attempts to look into just a minuscule portion the mass amounts of data Formula 1 teams handle.

#### For many years the Formula 1 organization has been looking into the many way in which it can minimise it's impact on the environment while still keeping true to the sport of racing. But what about its reverse? What about the environment's impact on Formula 1? Does the weather really affect the the sport? I think we all know the answer to this as anyone who has driven a car at normal speed on a normal road would tell you it does. But how and where on a race circuit does it affect Formula 1 cars and their drivers? And which factors produce the biggest impacts? These are the questions I set out to find.


## Technologies
#### For this project I used Python 3.12.7 in Jupyter Notebooks. Pandas, numpy, and requests libraries were all utilized in the analysis and to pull the APIs from my data source, https://openf1.org/.

#### For final cleaning and dashboarding, I utilized Tableau and its Story function.

## Problems & Hurdles
### Getting the Data 
####  Finding a database for a data-rich topic such as Formula 1 isn't difficult. Find the specific data you need out of ocean of data and databases is a bit of a different story. However OpenF1 provided me a way of finding just that. I was able to find the weather data, lap data, race data and even some car telemetry data that would all be utilized.

### Normalizing the Data
#### Getting the data needed was almost the easy part, getting the data normalized was the opposite. Formula 1 is an international motorsport and therefore does not always use the imperial system of measurement. Then ther is the matter of timing. Formual on cars travel at outrageous speeds and are subject to be times using one one thousandth of a second. It is not often that when comparing  data that timing is going to line up correctly. This tool many hours to normalize and make work correctly.
### Hurdles
#### While the data is relatively cut and dry, there is A LOT of it. It was difficult to sift through it and pull only what was relevant to my project. An example of this is that weather has the potential to impact several aspects of the sport. Which ones are relevant and which one are accounted for by the teams before the race and adjustments made so those aspects no longer have an impact? 

## Link to Dashboard
#### https://app.powerbi.com/groups/me/reports/7b2f603e-5cad-4b84-ac2d-c8382e6a311e/ReportSectiona0519b7ce424d578cf59
