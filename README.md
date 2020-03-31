# Report-Automation
Automated Reports (Performed preprocessing steps and plotted graphs and then attached the plots and data into the mail)

Extracted all the neccessary librariries to perform preprocessing visualization

extracted the data from a url(Production server)

performed preprocessing steps
  1.Identified the required data from the json file.
  2.Created several dictionary files to tag a key with several values
  3.Concatinated and merged all the dictionaries into a single dataframe
  4.Added a column called breached with the conditions.
  5.Used Try Except clause to handle errors while fetching comments
  6.Filtered the required data to visualize and saved the plots into png #can alse written into html to have interactivity of graph
  7.Data is written into excel sheet.
  8.All the plots and data has been attached in the email using smtp with receivers email,sender's email and password.
