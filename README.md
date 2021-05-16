# productivity-tracker

## Install Requirements

Download the repository and navigate into folder which contains manage.py file

1. pip install virtualenv
2. python -m virtualenv environment
3. environment\Scripts\activate.bat
4. pip install -r requirements.txt
5. python manage.py runserver

## About

An advanced version of a todo, where each list has a score associated with it. At the day's end, the total score is computed, and it is saved in user's day's score. A profile page shows a detailed statistics version of the progress.

## Home page

Here you can view existing todos, and add a todo and assign a score level basaed on your priority. At the day's end, just mark the tasks as completed and submit for the day.
The total score for the marked todos is computed. Go to profile page and view your statistics.

<img src="https://github.com/TeslaLord/TeslaLord/blob/main/todohome.PNG"> </img>

## Profile page

Statistics are generated based on your score - average score, highest score, highest streaks and so on...

<img src="https://github.com/TeslaLord/TeslaLord/blob/main/todoprofile1.PNG"></img>

INTERACTIVE graphs are generated for your score and streak. The graphs can be hovered over, zoomed in, and more...
<img src="https://github.com/TeslaLord/TeslaLord/blob/main/todoprofile2.PNG"> </img>
