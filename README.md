# MusicRoom

# Description

This project aims to tackle all the concepts necessary to the creation of a mobile, con-
nected and collaborative application taking into account the constraints of a real product.

You will have to work on the client/server architecture of you solution, take decisions
for you data storage, define an API that will be used as a communication channel between
your server and your clients, anticipate the problems of ramp-up and securing, and learn
to work with third parties, integrating external SDKs.

# Technologies used
 - Django
 - Python
 - Deezer API
 - Javascript
 - AJAX
 - MySQL
 - HTML
 
# Group Members:
 - Nathi Mncube - nmncube@student.wethinkcode.co.za
 - Kudzanai Gomera - kgomera@student.wethinkcode.co.za
 - Joshua Kwayiba - jkwayiba@student.wethinkcode.co.za


# Subjects

There are a lot of subjects. You should dispatch the different tasks between your
project team members.
The following services will have to be implemented:
• Music Track Vote - Live music chain with vote,
• Music Control Delegation - Music control delegation,
• Music Playlist Editor - Real time multi-user playlist edition
To register for this project, you will have to validate the First Internship. How-
ever, depending on the part you’re interested in, you should also validate those projects:
• Mobile part - ft_hangout and/or Swifty Companion
• Backend part - Hypertube

# How to Run

* make sure to run the app on http://localhost:8000 for the oauth2 to work proper follow the following cmds

# RUN

~ python3 manage.py makemigrations

~ python3 manage.py migrate

~ python3 manage.py runserver localhost:8000

# Incase you face site not matching ... when resetting password run the following commands

~ python manage.py shell
~ from django.contrib.sites.models import Site
~ Site.objects.create(domain='localhost:8000', name='localhost')
