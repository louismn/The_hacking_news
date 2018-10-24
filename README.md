# README
### Réalisé par 
### Louis Martin du Nord 
### Priscille de la Tour @Pris


### Requirements
   ```
   Ruby version : 2.5.1 
   ```
   ```
   Ruby on Rails : 5.2.1
   ```



### This is the database side to our rails application The hacking news, which aims to become later a dashboard where users can create and comment articles.


### They will also be able to comment comments!

### To run the app you just have git clone the this repositiry and do the ```bundle install``` to install the gems from the Gemfile.


## Contents

### We created 3 models, which each contains 1 table as follows:


### A model Lien for which each link has a user
### Table liens:
- user
- lien

### A model AComment in which we link each lien with its comments
### Table a_comments
- a_comment
- lien_id

### A model BComment in which we link each primary comment (AComment) to its sub²comment (BComment)
### Table b_comments
- b_comment
- a_comment_id







