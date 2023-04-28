# README

This is a simple blog developed with rails using RSpec functions to test my feature (posts).

Things you may want to cover:

* Ruby version 2.7.2

* Rails version 'rails', '~> 6.1.6', '>= 6.1.6.1'

Important Gems:
  gem "factory_bot_rails"
  gem "rspec-rails", "~> 5.0.1"
  gem "faker", git: "https://github.com/stympy/faker.git", branch: "master"
  gem "shoulda-matchers", "~> 4.5"
  
  The main thing here is to test posts, so doing "rspec spec/requests/posts_spec.rb" in the terminal should test exactly what I need
  And if we run the server (rails s) and test manually it will correspond to my posts_spec.rb.
  
  In posts_spec.rb I set valid params for "creates a post" and invalid params when I can't create a post
  Context for invalid params in this case is:
  - When I don't type anything and hit "create a post"
  ![WhatsApp Image 2023-04-28 at 15 53 07](https://user-images.githubusercontent.com/89879410/235230052-602646a8-9671-44af-9a28-c90cc7d19bd2.jpeg)

  - When I only type something in "Title field" and hit "create a post"
  ![image](https://user-images.githubusercontent.com/89879410/235229828-346bb897-be34-41c6-9fd5-f22c586e07cd.png)

  - When I only type something in "Body field" and hit "create a post"
  ![image](https://user-images.githubusercontent.com/89879410/235229763-9094b5ae-9af8-453c-8031-05872575e0f0.png)

It fails and will not create a post


Simple, but I tested my concepts and could understand more how RSpec works, how to test funcionalities and improved more my techniques with Ruby on Rails
I still need a lot to learn. :)
