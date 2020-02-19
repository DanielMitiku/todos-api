# Todos-API

> This is a tutorial made to build a RESTful JSON API With Rails with JWT authentication. It is based on this article - https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-two

## Built With

- Ruby
- Rails API Only
- JWT
- JSON

## Getting Started

To get a local copy up and running follow these simple example steps.

- Clone this repository to your local machine using `git clone https://github.com/DanielMitiku/todos-api.git`.

- Run `cd todos-api` to move into the app directory.

- Run `bundle install` to install all the dependencies.

- Run `rails db:migrate` to migrate the database.

- Run `rails s` to start the server.

## Examples using httpie

- To signup `http :3000/signup name=daniel email=daniel@daniel.com password=foobar password_confirmation=foobar`. This will return authorization token.

- To create todos `http POST :3000/todos title=todo1 Authorization:'put authorization token here'`

- Getting todos `http :3000/todos Authorization:'put authorization token here'`.

## Contributor

👤 **Daniel Mitiku**

- Github: [@danielmitiku](https://github.com/DanielMitiku)
