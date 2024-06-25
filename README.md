This project is a text-based technical support ticketing application designed to operate within a Jupyter Notebook. 
The application helps users create and manage support tickets by categorizing issues into predefined types, which are specified in an external file.
The program initializes by loading issue categories and their respective subcategories from the categories.json file.
Then, the user is shown a list of issue categories to choose from.
After selecting a category, the program displays the relevant subcategories.
The user picks a subcategory and describes the issue.
The application then creates a new ticket, assigns it a unique ID, and saves it.
The user can also request to view all created tickets.
Each ticket is displayed with its unique ID, selected category, subcategory, and the issue description.
