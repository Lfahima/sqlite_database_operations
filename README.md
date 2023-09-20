# sqlite_database_operations
This is assignment #3 for HHA 504

## Details on the datasets you've selected.
I selected the StonyBrook data set that was provided by Professor Hants under the data file. This data set was really interesting because it included the de-identified id of a patient under the column "code" and  a column on services that the patient had, and the charge of the specific service. The data set also included the discounted prices of the services listed, and what various insurance companies were covering. 
I also tried to find my own data set, so I looked up various hospitals price transparency machine readible files. I came across Northwestern Memorial Hospital which offered a link for standard charges as a json file that worked. Because this file had 'utf-8-sig' encoding I had to add the following `encoding = 'utf-8-sig'` to the `read_json` function (I got this solution from stackoverflow and it worked). 


## An account of the exploratory data analysis process.
For both my data sets I slected, I conducted the following: 
I Calculated the mean, mode, median, range, variance, standard deviation of three different columns.
I identified missing values of the two data sets and replaced them with 0. 
I visualized data distribution using histograms for 3 columns. 
I calcuated frequency counts for categorical variables, using 2 coulmns from the data sets.

## Instructions to replicate your SQLite database setup.
I used google colab, and the sqlite3 package to complete the sqlite portion of the assignment is under sqlite3. I utilized the slides provided in class and under the slides files to get the codes needed to create a fiction table on patient information.
