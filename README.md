# SG Birds

A brief layout of project work in different screen version

<img src="./readme/sgbirds-mockup.png" height="450" alt="Site Map template">

The website can be accessed [here](https://sgbirds.netlify.app/)

Use the email 'howudoing@gmail.com' to test out the profile page of the website.

## Background

## Project Overview

For bird enthusiasts in Singapore, their main concerns will be where they can find birds to watch or take photos of, and to update like-minded enthusiasts of where to find certain species of birds in Singapore.

## The Five Planes UI/UX

### Strategy

#### Organisation's Goals
To create a community for fellow birds watching and phototaking enthusiasts to communicate and help one another find find the birds they are looking for.

#### User's Goals
As a bird watcher using the website, I want to be able to share with fellow bird watching enthusiasts birds that I have spotted.

As a bird watcher using the website, I want to be able to find location of birds that I am interested in, so I can go down and take photos of them.

As a bird watcher using the website, I want to find fellow bird watchers to communicate and share my experiences with.

1. **Organisation**
    - Objective: To have a centralised space to contribute and search for different birds in Singapore.
    - Needs:
        - To search for different bird species in Singapore
        - To be able to contribute after spotting a bird
    - Demographics and charactertistics:
        - Teens and adults
        - Enthusiastic about birds and/or photography
        - Used to browsing the internet
    - Pain point:
        - Need to out about locations for a bird species that the user wants to watch or take photos of

User Stories | Acceptance Criteria(s)
------------ | -------------
As a bird watcher using the website, I want to be able to share with fellow bird watching enthusiasts birds that I have spotted. | Users should be able to easily share the location where they have spotted the birds at by the neighbourhood it was spoteted at and the latitude and longitude through usage of a map.
As a bird watcher using the website, I want to be able to find location of birds that I am interested in, so I can go down and take photos of them. | Birds should be searchable by the bird family it belongs to and user should be able to find the location it was spotted at easily.
As a bird watcher using the website, I want to find fellow bird watchers to communicate and exchange my experiences with.| Users should be able to comment on each others bird findings to encourage users to post and communicate with one another.

### Scope

####
Database 

<figure>
    <img src="./readme/erd.png" height="450" alt="Entity Relationship Diagram">
</figure>

ERD is drawn up to demonstrate the different relationship between enitities for the site before proceeding to model the database in MongoDB.

#### Content
Content in the website will be crowd sourced from the public and therefore, clear presentation of data contributed by users is essential. A landing page is included as well to showcase our branding and allow users to understand hat our website is about at a glance.

#### Functional
- Search function against attributes such as bird family and tags.
- Filter function of all sightings posted based on bird size, bird colours and neighbourhood spotted.
- Create new sighting function
- Edit and Delete function of each sighting
- Commenting function of each sighting
- Add and remove function of each sighting to user's favourites
- Registration and verification on email is included for actions performed on sightings, favourites and commenting

#### Non-functional
- Mobile responsiveness: Website should be mobile first and users should be able to navigate th webiste comfortably on their mobile devices.
- Accesibility:

### Structure

<figure>
    <img src="./readme/SiteMap.png" height="450" alt="Site Map template">
</figure>

### Skeleton

<figure>
    <img src="./readme/WireFrame1.png" height="450" alt="Wireframe">
    <img src="./readme/WireFrame2.png" height="450" alt="Wireframe">

</figure>


#### Colour Scheme
A burgundy, greyish-blue cream colour scheme was used to match the logo and generated by colour palette.
The colours chosen are warm to give the users a pleasant viewing experience.

## Testing 
Testing cases can be found [here](/readme/readme/Sgbirds-testcase.xlsx)

## Dependencies and Sources

### Backend
| Tech  | Usage |
| ------------- | ------------- |
|1. [Express](https://expressjs.com/)| Framework for routing to project's endpoints.
|2. [MongoDB Node Driver](https://www.mongodb.com/docs/drivers/node/current/)| To access database on MongoDB using their API
|3. [cors](https://www.npmjs.com/package/cors)| Middleware to enable CORS
|4. [dotenv](https://www.npmjs.com/package/dotenv)| To separate code from envrionment variables

### FrontEnd
| Tech  | Usage |
| ------------- | ------------- |
|1. [React](https://reactjs.org/) | Frontend framework |
|2. [Axios](https://axios-http.com/) | HTTP client to Express server endpoints|
|3. [Bootstrap](https://getbootstrap.com/) | Served as base styles for React App|
|4. [React-Bootstrap](https://react-bootstrap.github.io/)| Served as base styles for React App|
|5. [Sweetalert2](https://sweetalert2.github.io/) | Base style for alert pop ups in React App|
|6. [Leaflet](https://react-leaflet.js.org/) | Render map and map functions in React App|
|9. [OneMap](https://www.onemap.gov.sg/) | To retrieve latitute and longitude from its API by address search|
|8. [React-Select](https://react-select.com/home) | Styling of dropdown select dynamic adding|
|10.[Dynamic-Adding](github.com/)| referred to xunne899 to assist in completing it

### Platforms and Software
| Tech  | Usage |
| ------------- | ------------- |
|1. [Git](https://git-scm.com/)| For version control|
|2. [GitHub](http://github.com)| For repository|
|3. [Gitpod](https://gitpod.io/)| IDE for code editing|
|4. [Heroku](https://www.heroku.com/)| Deployment of Express server|
|5. [Netlify](https://www.netlify.com/)| Deployment of React app|

