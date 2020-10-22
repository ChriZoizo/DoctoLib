# Project DB From THP
Week 5, Day 4 (sept - dec 2020)


All the following projects have been created with Rails.
All the following DB are functionnals

---


## DoctoLib DB

This is a project that simulates a medical database for Health Professionals.
By default, this DB contains tables (and relational table) for "Patient", "Doctor", "City", "Specialty" and "Appointment".


## Air B n'Dog

This project aims to provide a simple DB model, corresponding to the activities of a website that would allow to connect dogs owners with dogsitters.
By default, this DB contains tables for "DogSitter", "Dog", "Stroll" and "City"


## The Gossip Project 

There is the last project. This is the firsts steps of my first personnal project for fun. This DB may be the DB for a website like "Twitter".
Users may create Gossips, like, comments, and soon comments the comments ! XD
Right now the DB have only the tables (and relational tables) for "User", "City", "Gossip", "Tag", "Private Message".

---

# How to use ?

## How to install
-Download and unzip the project from https://github.com/ChriZoizo/DoctoLib/new/master?readme=1. 

-With your terminal, place path into the root folder of project, and do :
```ruby
bundle install
```

## How to up the db
-Always in the root folder, do:
```ruby
rails db:migrate
```

## How test DB 
-for ever, and ever, in the root folder, do:
```ruby
rails c
or
rails console --sandbox #for test without any DB save when you quit
```

! For more informations visit : https://guides.rubyonrails.org/


-------

# Thanks To

My teamate, the others teamates and ruby (and rails) community

# Contact
-Chris : Christeufeur83@gmail.com
-Flo : ???????.??@????.???

