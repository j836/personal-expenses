# personal-expenses
lets see how does getDateString work?
getDateString is called from the view layer with the help of templating insid createListItem function
We pass the 3 elements of expense object in the function createListItem out of which it takes the third parameter viz. moment
The same is passed as argument to getDateString()
In getDateString we format the date and return the fornatted date back which is then rendered in the view layer.
And createListItem is called by every item present in expenseItemList.
We achieve this with the help of map function which first returns an array of strings.
But with the help of join function and (" ") <-- this as argument the work is done.
