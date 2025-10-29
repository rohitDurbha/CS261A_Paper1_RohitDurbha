# More Than Just Yards: How Passing EﬀiciencySeparates the NFL’s Best Teams

## Author(s) and Date of Submission
**Author:** Prasanna Sai Rohit Durbha  
**Date of Submission:** October 28, 2025

## Project Structure

- `data/`  
  Contains the NFL team statistics dataset used in the analysis.

- `paper/`  
  Main analysis and report documents, including references and any supplementary materials.

- `.gitignore`  
  Specifies files and folders excluded from version control (.DS_store).

- Other scripts or notebooks as needed for the analysis.

## Description

This project investigates whether a team’s **average offensive EPA per pass** predicts its **season-long score differential** (points scored minus points allowed). Using the NFL Team Statistics dataset, a simple linear regression model was fit with score differential as the response and offensive EPA per pass as the predictor.

The results show a strong positive association: a **0.1-point increase in EPA per pass corresponds to an expected 57-point improvement in season score differential**. While passing efficiency explains over half the variation in point margins, other factors such as defense, rushing, turnovers, and special teams account for the remaining variability.

## Use of External Resources (including LLMs)

External resources were utilized for this project.  
- **LLM-based chatbots** (such as ChatGPT) were used for code correction and to solve some rendering issues with quarto (link to logs: https://chatgpt.com/share/68d47062-0a18-8007-b73d-1263d0600038).  
- No external datasets were used other than the NFL team statistics dataset specified below.  

## License for Dataset

The NFL Team Statistics dataset used in this project was obtained from the SCORE Sports Data Repository (https://data.scorenetwork.org/football/nfl-team-statistics.html).  
**License:** Please refer to the SCORE Data Repository for specific licensing policies regarding data use. If no explicit license is listed, usage is assumed to be permitted for academic/non-commercial research.  


## R
The analysis for this Regression report was done on RStudio (https://www.R-project.org/)
