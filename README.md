# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


# models
### Items
  # fields:
   - id(UUID)
   - title(String)
   - price(Integer)
   - description(String)
   - type(String)
   - image(String)
### Tables
  # fields:
   - id(UUID)
   - order_items(Array)
### Orders
  # fields:
  - id(UUID)
  - table_id(UUID)
  - status(String)
### Staff
  # fields:
  - id(UUID)
  - name(String)
  - role(String)





      