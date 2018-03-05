# opioid_overdose_analysis
BC Open Data Day Hackathon 2018


---- note on this project ----
we ended up abandoning this project to work on Coral app with Team Oceanview
---- end of note ----


### Team Name

*???*

### Team Members

- [Akshi Chaudhary, Data Scientist/Analytics Professional](https://www.linkedin.com/in/akshi-chaudhary/)
- [Jill Cates, Data Scientist/Full-Stack Web Developer](https://www.linkedin.com/in/jill-cates-44bb9147/)
- [Peter Lin, Data Scientist/Pharmacist](https://www.linkedin.com/in/peterlinmds/)

## Prototype Problem Statement
*A clear statement of the problem your team has identified to address through the project. Use this problem statement as the basis to ideate around. Research and validate the problem to test if it is an issue, or if others are already addressing in. You may need to pivit your problem statement, and ideas around approach depending on what you discover about the issue and resources available.* 

*This will help focus your approach to addressing the challenge.*


### Data sources:
1. [accidental drug related death USA from data.gov](https://catalog.data.gov/dataset/accidental-drug-related-deaths-january-2012-sept-2015/resource/44580a89-a260-4844-8ead-35736f395389)
- Size ~ 8100 cases
- Features:
    - date
    - demographics: sex, race, age, residence city/state/county
    - death city/state/county
    - injury description
    - injury locatoin
    - drug type: heroin, cocaine, fentanyl, oxycodone, oxymorphone,EtOH, hydrocodone, benzodiazepine, methadone, amphet, tramad,morphine (not heroin)
2. [Medical Examiner opioid death records in Cook County, Illinois](http://opioidmappinginitiative-opioidepidemic.opendata.arcgis.com/datasets/6c7ae2a98a8e4aedaf427e03999c89ed_1) Thank you Gillian! :smile:
- Size: ~ 2400 cases
- Features: 
    - incident location (lat/long, city)
    - incident date
    - death date
    - demographics: age, gender, race, latino
    - primary cause, secondary cause, manner, gunrelated
    - injury description
    - opiods
3. [opioid overdose data from Kaggle](https://www.kaggle.com/apryor6/us-opiate-prescriptions/data)
- provides opioid prescriber information such as credentials, specialty, and drug that was prescribed
- provides statistics on opioid-related deaths for each state in the U.S.
4. [Fraser Health ER data](https://github.com/healthhackathon/Overdose-Emergency-Department-data-YTD-2016) Thank you again Gillian! :smile:
- provides (aggregated data) suspected opioid overdose and overall overdose events by community.
- provides (aggregated data) Number of suspected overdoses by Fraser Health hospitals, overall and among those who were homeless.


### VODday-Hackathon-Submissions

This is a sample submission repository for Open Data Hackathon Projects. You can [fork this repo](https://help.github.com/articles/fork-a-repo/) and use this as a starting point. You do not have send a pull request for this repo. This is just a sample of what your repo can look like when you submit it to us as part of the final process for the hackathon.



### Prototype

a shiny app that integrates key features to predict high-risk opioid-overdose patient groups


### Presentation
*Link to your presentation or any related visuals you want to share.*


### Next Steps
*Continue to improve the app to include more data points using public and non public data sets*



### Setup
#### Install Dependencies

