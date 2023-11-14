# To-Do application written with ASP.NET core MVC

This is a Fullyfunctional CRUD To-Do Application where you can stay organized for your day to day activities.  
It can be used for multiple purposes such as shopping lists, taking notes or planning an event.

## What was done, step-by-step:

- Create the TodoItem model
- Create the _Form.cshtml file
- Add partial to the _Layout.html to display our form
- Create some code for the _Form.cshtml and bound the TodoItem model with it
- Add the SQLite database
- Create the Insert method into our controller
- Create the GetAllTodos method to display entries from our database
- Add using statement to the _ViewImports.cshtml
- Create the ViewModel dir inside the Models dir and then a new file called TodoViewModel.cs
- Bound the Index.cshtml to the TodoViewModel with the declaration of the model on top
- Include @using Todo.Models.ViewModel to the _ViewImports.cshtml
- Add some JS with ajax for the delete button
- Create the Delete method
- Add the Update button
- Add some JS with ajax for the Update button
- Create the PopulateForm method to get an item
- Create the GetById method to get an item from the database
- Create the Update method
- Add some styling

That's it! We've done!

## Quick start

```
git@github.com:sava9ecode/todo_mvc.git
create the SQLite database
dotnet run
```

Enjoy your journey!
