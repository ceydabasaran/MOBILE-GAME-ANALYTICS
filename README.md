# MOBILE GAME-ANALYTICS
It is game metrics analysis for 3 different games.

There is 3 datasets for 3 different games.

**Below are the 2-letter codes for selected countries.**

* DE - Germany
* GB - Great Britain, United Kingdom
* JP - Japan
* US - United States of America

**Below are the 2 platform abbreviations.**

* iOS, itunes => Apple - iOS
* Android, Google => Google - Android

### Datasets

**Installs:**
Installs dataset is a snapshot from raw data which contains user cohort information. There are 3 columns;

* InstallDate
* App-Country-Platform information
* UserCount (number of users in cohort)

**eCPM:**
eCPM dataset is a snapshot from raw data which contains eCPM information for related user cohorts. There are 6 columns;

* Date
* App
* CountryDashboard
* PlatformDashboard
* Format
* eCPM

**Impressions:**
Impressions dataset is a snapshot from raw data which contains eCPM information for related user cohorts. There are 6 columns;

* Date
* Game
* CountryName
* PlatformName
* AdFormat
* Impressions

### NOTES: 
**1) The dates are arranged as follows.**
* Use commas for digit separators and 0 significant figures for high numbers such as 1,267 - 35,456 - 123,587...
* Use date format in MM/DD/YYYY.

**2) Comparisons were made based on the following metrics.**

* Interstitials impressions per user: ImpU (Int) 
* Rewarded impressions per user: ImpU (Rew) 
* Estimated revenue: Est_Revenue =  InterstitialCount * eCPM (Int) + RewardedCount*eCPM (Rew)
* Average estimated revenue per user: ARPU
* Maximum eCPM: Max_eCPM
* Minimum eCPM: Min_eCPM
* Average number of users for last 3 days: Ro3_Avr_Users
* Average number of users of previous week: Pw_Avr_Users

