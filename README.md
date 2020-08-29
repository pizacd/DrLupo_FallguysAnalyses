# **Analyzing DrLupo's FallGuys Games**

[LinkedIn](https://www.linkedin.com/in/douglas-pizac-ms/)
[Kaggle](https://www.kaggle.com/pizacd)

DrLupo is one of the most popular streamers on [Twitch](https://twitch.tv/drlupo). As of August, he began playing FallGuys: Ultimate Knockout, a whimsical combination of battle royale and minigames. The purpose of this repository was to analyze his gameplay, create visualizations and provide recommendations for an upcoming tournament.

## Wrangling the Data

Created a table in Postgres SQL. From there, I created a dataset by watching gameplay footage on Twitch. Once all the data was compiled, it was exported as a .csv file.

## Cleaning the data

Using Python, I separated each round into it's own dataframe. All rows with null values were removed, and then concatenated back into one master dataframe. Any mispellings or wrong values were replaced, and then the dataframe was exported as an Excel spreadsheet.

## Visualizing the data

Imported the Excel file into Tableau, where I created visualizations of most common game modes played, win percentage and victories over time. All these can be found on my [Tableau](https://public.tableau.com/profile/douglas.pizac#!/vizhome/drlupo_fallguys/Fallguys?publish=yes) page. 

### Update: 8-29-2020:

On 8-27-2020, DrLupo showed my Tableau story live on his stream in front of tens of thousands of viewers. The following day, he showed it again to his tournament team who were all live streaming, resulting in my analyses being viewed live by over 30,000 people on Twitch.

Using the data I compiled along with my recommendations, DrLupo's team finished the regulation rounds in first place and ended up 5th overall, securing a prize of $3000.