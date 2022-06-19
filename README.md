# Zuri-task-django-models

* Make a new GitHub repository with a README.md file and a.gitignore file for Python.

* Clone it to your machine/computer, which will create a new folder containing your repository's contents on your PC.

* Create a new virtual environment named.env in that folder and install Django there.

* Make a brand-new Django project. Make the project's name your Zuriboard Student ID.

* Using the Django startapp command, create a new application. The app's name should be blog.

* Add the blog app to the INSTALLED APPS list in main projects.

* In the blog app, create a new model called Post. The following fields should be included:

Post

--------

1. Title : A string of maxlength 200, use Django’s models.CharField

2. Text : Any amount of text, use Django’s TextField

3. Author : A Foreign Key to the current user model. Make use of Django’s get_user_model function.

4. Created_date : A date-time column, use Django’s models.DateTimeField.

5. Published_date : A date-time column, use Django’s models.DateTimeField.

6. Create migrations for your new model using the makemigrations Django command.

7. Run all migrations using the migrate Django command.

8. Stage and Commit your Django project and push your changes to your GitHub repository.

9. Ensure your final code/submission is on the default branch of your GitHub repository.
