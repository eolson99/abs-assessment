This repository houses files for a group assessment based on API calls to the Census Bureau for the Annual Business Survey (ABS) dataset. The calls were focused
on business firms in the 'Professional, scientific, and technical service' category of the North American Industry Classification System (NAICS) code.

What's included:
- An ETL report, expressed as a jupyter notebook, detailing the API calls, extraction of data from the calls and storing them as panda dataframes and cleaning 
and transforming the dataframes to address our group-questions:
  - What are the trends in pay across US states for firms in the above category.
  - What aspect of the industry is being adpoted the most on a per-state basis? (in our case we focused on AI and Cloud-based firms)
  - What aspect of the industry is being sold the most on a per-state basis? (in our case we focused on AI and Cloud-based firms)
  - Where might the industry be headed based on these trends? (high-level overview, since we only focused on two aspects) 
  
- We parsed our extracted/transformed data out as .csv's to make it easier for each group member to work on thier plots, these .csv's are saved in a folder called
csvs for refrerence.

- We stored the plots for our code in another folder called plots as individual jupyter notebooks, with each notebook addressing a group-question.

- our report discussing our plots and findings is also attached
