# Clickarte

This repository is a [json-server](https://github.com/Malu888/clickart-app-server.git) created to feed data into the React Application below.

#### [Client Repo here](https://github.com/Malu888/clickarte-app-client.git)

# Server Structure

## Collections

### imagenes

{
"id",
"descargas",
"categoria",
"location",
"img"
}

### comentarios

{
"imagenId",
"autor",
"rating",
"contenido",
"id":
}

## Used API Endpoints in the App

| HTTP Method | URL                  | Request Body                         | Description                  |
| ----------- | -------------------- | ------------------------------------ | ---------------------------- |
| GET         | `/imagenes`          |                                      | Sends all images             |
| POST        | `/comentarios`       | {autor, contenido, rating, imagenId} | Creates a new comment object |
| GET         | `/imagenes/:imageId` |                                      | Sends all details of a image |
| PUT         | `/imagenes/:imageId` | {description, img, categoria}        | Edits a image and details    |
| DELETE      | `/imagenes/:imageId` |                                      | Deletes a image object       |
| GET         | `/comentarios`       |                                      | Sends all comments           |
| DELETE      | `/comentarios`       |                                      | Deletes a comments object    |
| POST        | `/imagenes`          | {title, description, img, categoria} | Creates a new image object   |

## Links

### Collaborators

[Malu Dietrich](https://github.com/Malu888)

[Samuel Angulo](https://github.com/SLAE021)

### Project

[Repository Link Client](https://github.com/Malu888/clickarte-app-client.git)

[Repository Link Server](https://github.com/Malu888/clickart-app-server.git)

[Deploy Link](https://clickarte.netlify.app/m)

### Slides

[Slides Link](https://www.canva.com/design/DAGSmKMleww/LSIAkavN8mbfLUgEuEw0WA/edit)
