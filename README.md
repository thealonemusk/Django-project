
<h1>Django Social Media App - SOCIO</h1>
This is a Django-based social media application that allows users to create and share posts, follow and unfollow other users, and see their own and other users' activity on the platform.
<h2>
Installation</h2>
Clone the repository from Github:
Copy code
git clone https://github.com/thealonemusk/Django-project.git

<h2>
Create a virtual environment and activate it:</h2>

Copy code
python -m venv env
source env/bin/activate (for Mac/Linux) OR env\Scripts\activate (for Windows)
<h2>
Install the required packages:</h2>
Copy code
pip install -r requirements.txt

<h2>
Run the migrations:<h2>
Copy code
python manage.py migrate
</h2>
Run the development server:</h2>
Copy code
python manage.py runserver
Open the application in your web browser at 
<h2>
Usage</h2>
Register a new account or login with an existing one.
Create a post by clicking on the "Create Post" button.
View all posts on the "All Posts" page.
Follow other users by visiting their profiles and clicking on the "Follow" button.
See the activity of users you follow on the "Following" page.
Logout when done.


<h2>Contributing</h2>
Fork the repository.
Create a new branch: git checkout -b new-feature
Make your changes and commit them: git commit -m 'Add some feature'
Push to the branch: git push origin new-feature
Submit a pull request.
