## Project Name:  Expense Calculator Application

### Course Title:
Web Application Development

### Assignment Date:  
February 6, 2018

### Student Name:  
Laura Wright

### Project Description:
In this assignment we used JavaScript to make an expense calculator. We created id's in HTML that were referenced in the javascript file using the document.getElementById().value method. We also used the parseFloat() function, toFixed() method and innerHTML property and clearForm() method to ensure final values were displayed correctly as percentages and that the form could be cleared at the end.

### View Project:
https://laurawright7.github.io/lesson4_javascript1/

### Lessons Learned in the Assignment:
1. In order to connect information in HTML to JS, id's are created in HTML and are referenced in JS as a variable. In JS, you create variables that will use the id's that you have just created. For example, var shelterAmt = document.getElementById("shelterInput").value; - The variable or var, that is referring to the amount spend on shelter in JS is named shelterAmt. The value of how much is spend on shelter, is equal to the amount that the user typed into the space allocated for shelterInput in HTML.
2. Users enter information into the spaces provided and the numbers typed in are in the form of a string, or a textfield. In order to calculate the expenses, JS needs to know what the amount typed in is in a number format that can be used to calculate mathematical equations. To do this you use the parseFloat() function to change the form of the numbers from a text form into a float form, or a mathematical equation form.
3. In order to clear a form that has been completed by a user, the clearForm method is used. The HTML id is called up and then the innerHTML property returns the HTML content to blank. Double quotes are used to make a string space blank. For example, document.getElementById("totalExpenses").innerHTML=""; - The getElementById is used to call up the id in HTML called totalExpenses. The innerHTML property is then set to be blank by having the property innerHTML equal a blank string ie innerHTML=""



