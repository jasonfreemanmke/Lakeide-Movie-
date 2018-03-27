These are the files I am giving you for the Lakeside Project:

SQL Files:
  Lakeside_create_tables.txt  used to establish tables & views
    Therea are 3 view definitions in this file:
    1. CheckModelView1
       used in FilmEdit to show which categories a film is in
    2. FilmListView1
       used in FilmList page to show all films in a certain category
    3. FilmReviews
        used in MyReview page to show the film review a member has
  Lakeside_insert_data.txt    used to populate tables

Controllers:
  AdminController.cs

Views:
  FilmEdit.cshtml - Update/Delete film data
  FilmList.cshtml - show films and Create a "blank" film record

Models 
  Category.cs      Categories table related definition and data methods
  Film.cs          Films table related definition and data methods    
  FilmCategory.cs  FilmCategories table related definition and data methods 

ViewModels (folder inside of the Models folder)
  CheckModel.cs used in the film edit action method
  FilmEditVM.cs used in the film edit action method
  FilmReview.cs used to create a list of reviews from the filmreviews sql view
                you will use this in Write a review page

Image folder for film and member avatar pictures

Film_datax.txt files for synopsis and member reviews downloaded from
               Rotton Tomatoes and the Internet Movie Database sites

