# Movie Catalog - A Simple MVVM WPF Application with SQL Database
Welcome to Movie Catalog! Movie Catalog is a simple desktop application built with the Model-View-ViewModel (MVVM) architectural pattern using WPF (Windows Presentation Foundation) and SQL Database. It provides users with a convenient way to manage and organize their movie collection, including details such as titles, genres, release years, ratings, and more.

## Features
1. **User-friendly Interface:** Offers an intuitive and easy-to-use interface for browsing, adding, updating, and deleting movie entries.

2. **Data Persistence:** Utilizes a SQL database backend to store movie information, ensuring data persistence and enabling users to access their catalog across sessions.

3. **MVVM Architecture:** Follows the MVVM architectural pattern to separate concerns between the data model, view, and view model, facilitating maintainability and testability.

4. **Search and Filtering:** Allows users to search for specific movies by title, genre, release year, or other criteria, and apply filters to narrow down the list of displayed movies.

5. **Sorting and Ordering:** Supports sorting and ordering options to arrange movies alphabetically, by release year, rating, or other attributes, providing flexibility in organizing the catalog.

6. **Data Validation:** Implements data validation rules to ensure the integrity and consistency of movie entries, preventing the addition of invalid or incomplete information.

7. **Responsive Design:** Adapts to different screen sizes and resolutions, providing a consistent user experience across various devices and display settings.

## **Prerequisites**

You need the following tools in order to run/edit the solution.

- Microsoft Visual Studio (Latest recommended)

- Microsoft SQL Server (Latest recommended)

## **Getting Started**

The application requires a database to store the data. Follow the below
steps to setup database. 

1.      
Run the script 'Movie Catalog.sql' to create and
populate database (MS SQL SERVER is required)

2.      
Set the connection string

&ensp;&ensp;  i.        
  Open MovieCatalog.sln (Visual Studio is required)

&ensp;&ensp;  ii.      
  Go to Properties in Solution Explorer

&ensp;&ensp;  iii.     
  Go to Settings.settings

&ensp;&ensp;  iv.    
  Insert Name as 'connString', Type as (Connection String), Scope as Application and Value as Connection String of Database.

## **Project Structure**

**Resources:**
        
- *Assets:* Directory containing assets used in project
        
- *Fonts:* Directory containing fonts used in project

**View:**
        
- *AddPage.xaml:* Contains UI for Add Page
        
- *AddPage.xaml.cs:* Contains interaction logic for AddPage.xaml
        
- *EditPage.xaml:* UI file for Edit Page

- *EditPage.xaml.cs:* Contains interaction logic for EditPage.xaml

- *HomePage.xaml:* UI for HomePage
        
- *HomePage.xaml.cs:* Interaction logic for HomePage.xaml
        
- *MainWindow.xaml:* UI for Main Window (Parent Container)
        
- *MainWindow.xaml.cs:* Interaction logic for MainWindow

- *Search.xaml:* UI for Search Page

- *Search.xaml.cs:* Interaction logic for Search.xaml

**View Model:**
       
- *MovieViewModel.cs:* Contains code for View Model for Movie (Model)

**Model:**

- *Movie.cs:* Contains code for movie class (Model)

- *MovieRepostory.cs:* Contains database connectivity code and logic

## Usage
1. **Browse Movies:** Use the navigation controls to browse through the list of movies in the catalog. Scroll through the list or use search and filtering options to find specific movies.

2. **Add New Movies:** Click on the "Add" button to add new movies to the catalog. Enter the relevant details such as title, genre, release year, rating, etc., and save the entry to the database.

3 .**Update Movie Details:** Select a movie from the list and click on the "Edit" button to update its details. Make the necessary changes and save the updated information.

4. **Delete Movies:** Remove unwanted movies from the catalog by selecting them and clicking on the "Delete" button. Confirm the deletion to remove the movie from the database.

5. **Search and Filter:** Use the search bar to search for specific movies by title, genre, or other attributes. Apply filters to narrow down the list based on criteria such as release year or rating.

## Customization
Customize Movie Catalog to fit your specific requirements by modifying aspects such as the user interface design, database schema, data validation rules, sorting and filtering options, and additional features such as movie recommendations or integration with external APIs. 
