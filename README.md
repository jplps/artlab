# artLAB

Register art events all over the world, and locate the ones you want.

Our vision for the audio-visual events is that they can be displayed as ART LABORATORIES, comprehending all forms of human expression. Here you can find laboratories scattered all over the world!

We allow users to register cultural events. Users are able to filter events by area (city, state, latitude, longitude) and by it's art category(ies).

## Who Are We?

The human application and physical expression of creativity through skills and imagination in order to produce objects, environments and experiences IS art. And we believe that the most important form of expression with the reality by humans, is through the form of ART.

Major art constituents:
	- Visual (Architecture, Ceramics, Drawing, Filmmaking, Painting, Photography, Sculpting)
	- Literature (Fiction, Drama, Poetry, Prose)
	- Performing (Dance, Music, Theatre)
	- Applied Arts (Video Games)
	- Multidisciplinary Works

Some art forms combine visual elements with performance (e.g. cinematography), or artwork with the written word (e.g. comics). From prehistoric cave paintings to modern-day films, art serves as a vessel for storytelling and conveying humankind's relationship with the ENVIRONMENT.

## Structure

System: Dynamic Application
Main lang(s): JavaScript (ECMA) / TypeScript
Stack: Node / Express & Knex / React & React Native / Expo
Pattern: RESTful

### Server - The base backend with Node & Express

Responsable for business rules, defines how the app behaves. It connects with the db and any external services needed. It handles the complete authentication/authorization for the users, criptography and security. 

The usage of the RESTful pattern differs from the classic MVC (Model, View, Controller) because it doesn't return the full page to the user but the data the client needs to render the complete view in the frontend (usually in JSON - JavaScript Object Notation). 

Despite the differences, we can benefit from the pattern nomenclature to separate functionality. Besides, when we build the backend this way, the flexibility allow us to communicate successfully with the mobile app without a change.

### Frontend / Mobile - React & React Native with Expo

With React we at the edge of the componentization pattern. Responsable for the interface of the web & mobile system (all the listings, dashboards, etc, with HTML & CSS and more) with the user, it helps us deal with a lot.


## Check the app

If all went well, see localhost:3000 in the browser.

### Todos

#### Structure
- [x] Create folders to retain web ui & server
- [x] Initialize projects with npm
- [x] Install server & web dependencies
- [x] Create src/ folders in both projects dirs

#### Backend

- [x] Create and configure knexfile & knex
- [x] Implement server and database/connection
- [x] Create migrations and seeds
- [x] Implement routes
- [x] Create controllers with the avaiable routes

#### Frontend
- [x] Create-react-app in the frontend
- [x] Clear & Refactor
- [x] Create pages/ and components/
- [x] Implement SPA
- [x] Implement services/api
- [ ] Refactor Styles