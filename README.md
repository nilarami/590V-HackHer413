# Data Description:

We want to work with the application data submitted by the applicants of Hack(H)er413, which was conducted here at UMass. We have access to both 2019 as well as 2020 applications, which have been anonymized.  The data is in a tabular form. The number of records is 650 for 2019 and 755 for 2020. We have 19 attributes and 27 attributes for the years 2019 and 2020 respectively. While the 2020 dataset consists of a single table which includes what the applicant RSVP’d and if they actually attended the event, the 2019 dataset stores this information in a separate dataset, which has also been included in the data dictionary. We have an overlap of 22 attributes, which we plan to use for our visualization and analysis.

## Applications:
The main purpose of our visualization and analysis is to see if we can identify some trend which can help us predict who all/ how many people show up to attend the hackathon. From past data, only around 50% of applicants attended the hackathon, and if we could figure out why, we think it will greatly help the organizers in the future. We also think if we could visualize the workshops suggested by the applicants, the organizers would find it easier to decide which ones to conduct or add new ones. We hope to answer the following questions by the end of the project:

-Is there a way we can dynamically visualize states/universities/location where people are traveling from? 
-Is there a connection between attributes and why people who showed up? 
-Can we visualize workshop suggestions?

# Hack(H)er413 2019/2020 Data Dictionary 

## Event Applications - 2019 

| Column Title | Options | Description | 
|--------------|---------|-------------|
| UserID | Numeric Value | Value to correspond to Check In ID| 
| Status | Accepted, Waitlisted, Denied | Application Status to attend Hack(H)er413 2019| 
| Age | Numeric Value | Participants share what age they are |
| Gender| Woman, Non Binary | Participants share what gender they are |
| University | Open Ended | Where participant attends college | 
|Major | Open Ended | Participants share what major they are | 
|Grad_Year| Numeric Value | Participants share what year they are graduating |  
|LinkedIn | Yes, No | Whether they provided URL| 
|Github | Yes, No | Whether they provided URL | 
| Previous Attendance | Yes, No | Whether they attended a hackthon previously | 
| Education | Freshmen, Sophomore, Junior, Senior, Masters, PhD | Level of Education | 
| Pronoun | She/Her, They/Them | Participants share their preffered pronouns| 
| Disability | True/False | participants share whether they have a disability or not |
| Race | | | 
|Beginner_Track | True/False | Whether they are a beginner to coding and follow track available | 
| Workshops | FILL IN | What Workshops they are interested in attending | 
| Workshop Suggestions | Open Ended | What workshops they are interested in that's not available | 
| Teams | Yes, No | Whether or not they already have a team ready | 
| Excited About | Open Ended | Share their feelings about incoming Hack(H)er413 2019 | 

## Check_Ins 2019 

| Column Title | Options | Description | 
|--------------|---------|-------------|
| UserID | Numeric Value | Value to correspond Event Applications ID| 
| User Type | Attendee, Admin, Organizer | Role during hackathon | 
| RSVP | Yes, No | Whether or not they confirmed attendance prior to hackathon | 
| Checked In | Yes, No | Whether or not they attended Hack(H)er413 2019 | 

## Event Applications/CheckIns 2020 

| Column Title | Options | Description | 
|--------------|---------|-------------|
| RSVP | Yes, No | Whether or not they confirmed attendance prior to hackathon | 
| Checked In | Yes, No | Whether or not they attended Hack(H)er413 2019 | 
| UserID | Numeric Value | Identifier Value | 
| Status | Accepted, Waitlisted, Denied | Application Status to attend Hack(H)er413 2019| 
| Age | Numeric Value | |
| University | | Where participant attends college | 
|Major | Open Ended | Participants share what major they are | 
|Grad_Year| Numeric Value | Participants share what year they will graduate |  
| Gender| Woman, Non Binary | Participants share what Gender they are |
| Ethnicity | White/Caucasion, Asian/Pacific Islander, Multiple Ethnicities/Other, Black or African American, Prefer not to Answer, Hispanic | |
|Minor | Open Ended | Answer if they have any mninors| 
|Grad_Year| Ordinal Value | When participant is graduating |
|LinkedIn | Yes, No | Whether they provided URL| 
|Github | Yes, No | Whether they provided URL | 
| Other URL | Yes, No | Whether they provided URL that's not LinkedIn or Github | 
| Been to Hackathon | True, False | Have you ever been to a hackathon | 
| Previous Hackathons | Numeric Value | How many hackathons in general have you previously attended | 
| Previous Attendance at Hack(H)er413 | Yes, No | Whether they attended Hack(H)er | 
| Programming Skills | HTML/CSS, Javascript, SQL, Java, Python, Node.JS, Express, C/C++/C#, etc.| What Programming Skills they have | 
| Hardware Skills | Embedded Systems, Robotics, Circuits,  3D Printing, etc | What Hardware Skills they have | 
| Hardware Preference | Open Ended | List What Hardware they want to see at the event | 
| Other Skills | Open Ended | Other Skills they may have | 
| Any Hack | Open Ended | What is a hack you want to build at Hack(H)er413 | 
| Empower | Open Ended | How do you empower diversity? | 
| How did you Hear | Open Ended | How did you hear about Hack(H)er413 2020? | 
| Sleeping | Yes, No | Whether they are planning on sleeping at the event | 
|Beginner | Beginner, Beginner++ | Whether they are a beginner to coding and follow track available | 








