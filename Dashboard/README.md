# User interaction on Yandex media platform

## Scope of the project

**The goal**:
- Create a dashboard for managers

**Input data**: 
- We have data with users interactions on the platform on 24.09.2019 from 18:28 till 19:00

**Analysis structure**:
* Data overview
* Terms of reference
* Links
* Results

## Terms of reference
After talking with managers and database administrators, we wrote a brief terms of reference:  

* **Business task**: analysis of user interaction with Yandex.Zen cards; 
* **Use of the dashboard**: at least once a week;  
* **Main users of the dashboard**: content analysis managers;  
* **Data for the dashboard**:
    * History of events on the topics of cards (two graphs - absolute numbers and percentage);
    * Breakdown of events by topics of sources;
    * Correspondence table of the topics of the sources to the topics of the cards;
* **By what parameters should the data be grouped**:
    * Date and time;
    * The topic of the card;
    * The source topic;
    * Age group;
* **Importance**: all charts are of equal importance;
* **Data sources for the dashboard**: raw data about user interaction events with cards;
* **Database where the aggregated data will be stored**: additional aggregated tables in the zen database;
* **Data update frequency**: once a day, at midnight UTC
