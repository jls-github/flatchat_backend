# FlatChat

A realtime chat application. This repo contains our backend server and database.

## Technology Used

- Rails 6.0 API server
- Websockets via ActionCable
- Postgresql database
- Auth via Bcrypt and JWT
- Automatic deployment via GitHub and Heroku

## Features

- Login/Signup
- Conversation selection; currently there is only one 'main room' available.
- Send and receive messages in real time!
- View conversation participants
- Logout

## Installation/Deployment

- Local installation
    - Clone/download the project repo's main branch. `cd` into the main project folder, then run `rails db:migrate` and optionally `rails db:seed` to populate the database with some data. 
    - Finally, run `rails s` to start your server
    - Don't forget to grab a copy of our [frontend client](https://github.com/strangrjrjr/flatchat_frontend) and follow the instructions there!
- Deployed installation
    - Check out the rails server on [Heroku](https://flatchat-demo.herokuapp.com)

A project by [John Souza](https://github.com/jls-github), [Jazz Bozner](https://github.com/jazzbozner), and [Roger Robertson Jr](https://github.com/strangrjrjr).
