
# Trivia Quizzz

A simple trivia quizzz web app made using django


## Demo

[http://triviaquizzz.herokuapp.com/](http://triviaquizzz.herokuapp.com/)

& 
https://triviaquiz.redcrypt.xyz

  
## Features

- Google , Discord Social Login
- Import, export options for questions in multiple formats
- User Avatar in profile page { Social avatar from discord,google if connected else [gravatar](https://en.gravatar.com/) }
- More than 3k Questions (only on http://triviaquizzz.herokuapp.com not in repository) (Questions from OpentriviaDB)
- Play by categories

### Planned Features

- Better appearance on mobile
- More responsive webpages
- 404/500 Error page
- Meta data in html pages
- Leaderboard
- Public profiles
- Time limit of 15 sec in each question
- Submit questions (users can submit questions)
- PWA (Progressive web app) App 


    
## Installation

Fork & Clone this repository

Then run the following commands in that directory

```bash
  pip install -r requirements.txt
  python manage.py makemigrations
  python manage.py migrate

```
    
## Deployment
To create a superuser
```bash
  python manage.py createsuperuser
```
and then enter the details asked.



To deploy this project run

```bash
  python manage.py runserver
```

  
## Tech Stack


**Server:** Django

  
## License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
