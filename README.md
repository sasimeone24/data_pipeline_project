<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Web-Scraping, Cleaning, Filtering and Visualization
*Samuel Simeone Sanchez*

*DAFT-MX-2021/9/17*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The project consists of scraping the metacritics page in order to obtain information about the video games (release date, name, distributor, developer, etc). Later the data is cleaned, analyzed and finally visualized.

## Rules
The project itself has no rules, it simply consists of running it and it will do all the work alone.

The important thing to note is that you have to enter two pieces of information into the program, the number of pages and games to be obtained. The number of pages refers to the number of pages to analyze, that is, where the links to the games are found (see link to metacritics).

## Workflow
- The first step was to find a page to scrape. The page was on a topic that interests me and had no limitations in the robot.txt.
- The second step consisted in obtaining the code of the page, which was achieved with selenium .
- Then the information was cleaned and saved in a dataframe.
- The data obtained was analyzed.
- Finally, the data obtained through graphs was visualized thanks to the matplotlib and seaborn libraries.

## Organization
In the repository we have the data_pipeline_metacritics file, which is the python file that handles the process already described. On the other hand we have the Data_sets folder where the csv of the scraped data are saved.

## Links
[Repository](https://github.com/)
[Metacritics Page](https://www.metacritic.com/browse/games/score/metascore/all/all/filtered) 