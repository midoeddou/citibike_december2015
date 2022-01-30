# Analysis of the "JC-201512-citibike-tripdata" dataset

## Motivation
In the frame of the Udacity data scientist course, we're performing in the first project an analysis of the dataset of our choice. We'll then have to deliver our code in a jupyter notebook stored in a github repository, and present our main findings by writing a blog (in medium for example).

I chose the "JC-201512-citibike-tripdata" as it seemed like a relevant dataset for data visualization, and it triggered some questions I wanted to answer such as: 
- What's the citi bikes users profile like (age, gender, subscribers/one off users) ?
- What times of the day are the citi bikes more used ?
- What are the most active bike stations ?
- Are there different behaviors between citi bikes subscribed users and one-off users?

In case you're like me and wanted more details about "citi bikes" are: [this wikipedia link](https://en.wikipedia.org/wiki/Citi_Bike) will give you some information about the citi bikes concept.

## Installations
To be able to launch the jupyter notebook, you'll need to have the following installed:
- Python 3.0 version or above
- Jupter notebook
- The data analysis/visualization supporting libraries:pandas, numpy, matplotlib, seaborn and datetime

## Files description
This directory contains:
- the dataset `JC-201512-citibike-tripdata.csv` downloaded from Kaggle
- The jupyter notebook `citi_bike_ride.ipynb` containing the data analysis process: data import/preparation, data exploration/analysis followed by visualization and findings (in iterations rather than linear process, so bear with me!)
- This `README.md` file

## Findings

To discover the findings in detail, have a look at the [medium article](https://medium.com/@eddouhbanimehdi/and-you-are-you-also-a-citibiker-6e0def144600) about NYC citibikers and their habits!

If you're a bit too lazy to do so, below a recap of the major takeaways of our analysis:
- We learned about the profile of the CitiBike subscribers: mainly male young people between 20–40 years old
- We then looked at when and where people were taking their bikes: the middle of the week (Tuesday/Wednesday/Thursday) being the most active days, with a peak from 6 to 9am and 3 to 6pm. This indicates that most users bike to commute to work or to school.
- Finally, we examined the difference of behavior between one-off users and subscribers, as subscribers formed 94% of our dataset and therefore strongly influenced previous results: we learned that one-off users bike longer (about two to three times on average!) than the subscribers, and will mostly use the CitiBikes during Fridays or the weekends, which are the days during which CitiBikes are least used by subscribers.

## Licensing and Authors
I Must give credit to Kaggle for the data. Unfortunately once I tried to retrieve the licenses related to the data the dataset was not available in Kaggle! 
Otherwise feel free to use this code as you want to!
