## Blazor Server Application with EF Core

# Reference:

	    1 . I have prior knowledge about Blazor WASM 
        2 . I have re-created the application wrote most of every line by hand again to practice and get familiar with Server 
        3 . Here is the application , you can look into the commits since yesterday to Now.( or here is the Items it include)

 NOTE : I will be continuing by my own time. 

## ASP.NET Core 6 Blazor Server Application [EF Core]  

1. **Why Blazor Server and Entity Framework Core goes together rather in WASM need API to use EF Core.**  

2. **Create the Initial Blazor Server Project &  Setting up Entity Framework Core** 
      - Implement a DbContext 
      - Register the DbContext as a Service 
      - Move the Connection String to App Settings 
      - Add and Run the First Migration 
      - Apply Migrations at Runtime 
      - Seed the Database with Data 

3. **Reading and Showing a List of Data** 
    - Read the Employees from the Database 
    - Show the Employees in the User Interface 

5. Understand the **DbContext Factory** 
6. Inject and Use a DbContext Factory 
7. **Some work around to get familiar like (several work around)** 
    - Implementing Pagination 
    - Add and Use Parameter 
    - Handle parameter string Value controlled (too high or too low) 
    - Display a Pagination Component 
    - Show a Previous and a Next Button 

8. **Adding a New Data Item (Edit Form to get familiar like parameter, event call back** 

    - Create an AddEmployee Component 
    - Implement a Form 
    - Add Text Input Fields, Property-specific Validation Errors, Checkbox , Dropdown List 
    - Load the Dropdown Data 
    - Save the Employee to the Database 
    - Work around for valid and Invalid Submit 
    - Extracting the Form to introduce a new Component 
    - Create an Employee Form Component 
    - Implement Component Parameters 
    - OnSubmit Event Callback 
    - Handle the OnSubmit Event (practice) 

9. **Editing an Existing Data Item** 

    - Create Component for editing the model (Employee). 
    - Load the Employee to Edit 
    - Handle an Invalid Employee Id 
    - Load the Departments 
    - Show an Update and a Cancel Button 
    - Update the Employee in the Database 
    - Handle Errors When Saving the Employee 
    - Update the Department Id 

10. **Some work around to get familiar with Services Like Navigation Manager** 

    -  Navigate Back  
    - Store the Page State  
    - Navigate Back on Cancel 

 
