### Overview

Marvel provides a public API allowing users to explore their entire catalogue of comics, series, characters and relationships between the objects.

The API can be found here: http://developer.marvel.com/docs#!/public/

You'll need to create an account in order to obtain an API key.

### Task

Create an application that starts by displaying a list of Marvel comics or characters that can be searchable and/or filterable, and allows the user to drill down into the various entities contained within (comics, series etc).

How the user explores the relationships between the entities is up to you, so you can be as creative as you like when designing the front-end interface. However, the focus is not on design, just creative front-end interaction and a working prototype.

The task should be completed in two parts; purely as a training task to assist in ongoing work with Laravel and Vue.

You can tackle either first.

A Laravel application to consume the Marvel API.

The application should be fairly barebones, it's effectively a middleman, and could be argued it doesn't need to exist - but you're building it for training purposes.

It should run under the ``/api`` url (stateless) and is used purely to return data via AJAX in the JSON format.

You'll need to setup routing to handle API requests (e.g: ``/api/characters``).

For training purposes, please setup controllers for each entity which does the API consumption.

As above, this should be a middleman which queries the Marvel API, does any cleanup, and returns a JSON response so that the front-end can use the data for displaying.

- Laravel as the middleman for consuming the API
- Vue as the client-side technology, for displaying the data
- You can use Laravel's routing for returning views, or if you want, use vue router
