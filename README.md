# Easter-Calculator-website
I created a website that interacts with a Python program via CGI to inform the user of the day and month on which Easter falls in a given year that the user inputs. The website uses a form to allow the user to input the year, and radio buttons to specify how they want the output to be formatted.

The user can select between three different formats for the output:
Numerically, as dd/mm/year (for example: 12/04/2020).
Verbosely, with the full name of the month as day of named_month year (for example: 12th April 2020).
Both of these formats.

To achieve this, I wrote a Python program that calculates the date of Easter for a given year using the Gauss algorithm. I then used CGI to interact with this program from the website, passing in the year entered by the user and formatting options selected by the user.

The website was designed to be visually appealing and user-friendly, using CSS from an external stylesheet located on the server to format both the form and the output. The output of the program was displayed on the website in the selected format.

I also implemented a feature to add a superscript of either st, nd, rd or th to the day of the month in the verbose output format, which earned me an extra credit mark.

Overall, I successfully created a website that interacts with a Python program via CGI to calculate and display the date of Easter for a given year in various formats.
