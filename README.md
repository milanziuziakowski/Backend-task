# Backend-task
Destination of this repositorium is making operations on database, which is taking it's information from Omdb API.
1.First of all. The task which is performed in __"_main_"__is making database file by taking Titles from "movies.csv" file and then downloading every needed columns from API to new csv file ("movies_done.csv"). After downloading, dataframe with needed informations is tranformed to SQLite file, which is helping to perform operation on data.
2.Then there's making CLI which is using every programmed function to get gone required tasks

Use in terminal in this directory file TEST_CLI.py, which is perfomorming functions defined in TestFunctions.py
If you write "python TEST_CLI.py" , then you get help
for example you can write: python TEST_CLI.py filtr_by Director "Olivier Nakache, Éric Toledano"


(CLI has helping commands what user should write)

In Repositorium is a lot of .py files with tests of each function

Command which you can use in Command Line Interface are:
-"sort_by":
It can sort by chosen category

-"filtr_by":
It can filter table and print it by Director, Actors, Language (write one word at the end of the command
    It can also check which movies was nominated for oscar but didn't win any, the command is : "NotWin". 
    Check which movies won at least 80% of nominations, command "80wins".
    Check which movies earned over 100 000 000$ , command "80wins"
    
-"--add"

-"--highscores"
-
