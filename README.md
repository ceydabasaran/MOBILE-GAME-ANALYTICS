# GAME-ANALYTICS
It is game metrics analysis for 3 different games.

There is 3 datasets for 3 different games.

* Below are the 2-letter codes for selected countries.

DE - Germany
GB - Great Britain, United Kingdom
JP - Japan
US - United States of America

* Below are the 2 platform abbreviations.

iOS, itunes => Apple - iOS
Android, Google => Google - Android

### Datasets

**Installs:**
Installs dataset is a snapshot from raw data which contains user cohort information. There are 3 columns;

1- InstallDate
2- App-Country-Platform information
3- UserCount (number of users in cohort)

**eCPM:**
eCPM dataset is a snapshot from raw data which contains eCPM information for related user cohorts. There are 6 columns;

1- Date
2- App
3- CountryDashboard
4- PlatformDashboard
5- Format
6- eCPM

**Impressions:**
Impressions dataset is a snapshot from raw data which contains eCPM information for related user cohorts. There are 6 columns;

1- Date
2- Game
3- CountryName
4- PlatformName
5- AdFormat
6- Impressions

### NOTES: 
**1) The dates are arranged as follows.**
Use commas for digit separators and 0 significant figures for high numbers such as 1,267 - 35,456 - 123,587...
Use date format in MM/DD/YYYY.

**2) Comparisons were made based on the following metrics.**

* Interstitials impressions per user: ImpU (Int) 
* Rewarded impressions per user: ImpU (Rew) 
* Estimated revenue: Est_Revenue =  InterstitialCount * eCPM (Int) + RewardedCount*eCPM (Rew)
* Average estimated revenue per user: ARPU
* Maximum eCPM: Max_eCPM
* Minimum eCPM: Min_eCPM
* Average number of users for last 3 days: Ro3_Avr_Users
* Average number of users of previous week: Pw_Avr_Users

