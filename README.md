# Quizzy
## Why Quizzy?
Due to the outbreak of COVID-19, students and professionals have to perform tasks from home. Quizmaster is an Ed-tech idea to host and participate in quiz contests in a secure way, which can be used for educational purposes as well as just having fun with friends.
* Online platform to host Your quiz contest.
* Conduct and participate in quiz contest using unique contest ID.
* Instant result with in-depth analysis of your performance.
* Compete to grab your rank on the leaderboard.  

## Screenshot
![Quizmaster Homepage]()

## Working in brief
Users will have to create an account or sign-up first if they don't have one. Then they should log in. Now it would be good to go!
### Hosting a contest
* Click on the `Host your own contest` button to host a contest. An auto-generated unique contest-ID will pop-up. Now click on the `continue` button.  

* You can add questions by filling up the form and pressing `Add question` button and you may choose to delete innecessary questions as well by pressing the `Delete` button corresponding to each question.  

* After you finish setting up the contest press `Save contest and continue` button to get the contest ID. Copy and share it with the participants.  

* You can have a look at the leaderboard using the same contest ID.  

### Participating in a contest
* Click on the `participate in a contest` button to participate in a contest. You have to just give the contest ID shared by the host to participate.  

* The quizpage will open up. It has a timer on top (30 seconds per question on average). You can also navigate between questions using `previous` and `next` button.  

* The responses will be auto-submitted if the time is over or You may also click `Finish quiz and submit button` to do the same if you have already finished.  

* You can now see your score along with correct,unattempted,wrong answer statistics and your performance analysis per question.  

* You may visit the leaderboard using the same contest ID.  

#### ID for sample contest : 72b0a716-63e6-4d95-ac40-b3a114051cbf
## Technology used
* HTML
* CSS
* JavaScript
* JQuery
* BootStrap
* Django
* Sqlite3  

## Setting up the project in local machine
* Download or clone the repository into your local machine.
* Run `pip install -r requirements.txt` to install required modules.
* Run `python manage.py runserver` to run in test server in `http://127.0.0.1:8000/`.
* Run `python manage.py collectstatic` to set up static files.
* Run `python manage.py migrate` to set up database.
* Run `python manage.py createsuperuser`to create an admin user. You can visit the admin dashboard in `http://127.0.0.1:8000/admin/`.
* Boom! you are ready to go.
