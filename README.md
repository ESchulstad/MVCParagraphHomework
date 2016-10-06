# MVCParagraphHomework

The PureWow website is a blog featuring different articles pertaining to life, food, and other similar topics. MVC could be implemented into this site so viewers could create an account and login in order to save articles to read later or create a list of favorites so that they can always find their favorite articles from the site in one place. This would require a database that stores not only the user's account information, but also one to save the articles that they put into their lists. This way nothing is lost and the user can easily find them. 

The model part of MVC uses C# and creates the database where this information is stored. The view is what the user sees and where they will input their information and the controller navigates between the view and the model sending the information from the view to the model. 

The user will put their information into the view and create their lists of favorites and saved articles. The controller will take this information and pass it to the model. The model will update this information and makes sure the information is stored in a database. This way when the user refreshes all their new information is shown to the user by the view. 
