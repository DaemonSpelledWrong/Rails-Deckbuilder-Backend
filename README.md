# Magic Deckbuilder Deluxe
A deck building application for the card game Magic the Gathering.
All card data has been seeded from the <a href="https://scryfall.com/docs/api">Scryfall</a> api. - `https://scryfall.com/docs/api`

<a href = "https://youtu.be/yaA-Sau9FMk">See features video!</a>

## Requirements
---
- Ruby
- Rails

## Installation
---
Add the following gem lines to your Gemfile: 
```
gem 'rest-client'
gem 'bcrypt'
gem 'jwt'
gem 'simple_command'
gem 'pg'
```
and run `bundle install` from your shell.
The 'pg' gem is for the PostgreSQL database. 

## Usage
---
- Once the project is forked, make sure to run your migrations and seed your database. You can do this by running: 
  - `rails db:migrate`
  - `rails db:seed`
- Once you've installed the necessary dependancies and run migrations and seeds, host your backend on localhost:3000 by using the rails command: `rails s`

## Contributing
---
Contributions are currently unwelcome but suggestions and criticism on code quality are! This is a personal project for me at the moment.

## License
---
All card content and logos / images belong to Wizards of the Coast.
