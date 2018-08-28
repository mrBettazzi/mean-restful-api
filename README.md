# RESTful API example

## API provider
See `server.js` for DB settings.
Run `node server` to start the API provider.

## data model
```bash
var BearSchema   = new Schema({
    name: String
});
```
## usage
Use **Postman** 
`GET http://localhost:3000/api` to test the API
`POST http://localhost:3000/api/bears` to add a bear
`GET http://localhost:3000/api/bears` to list all the bears
`GET http://localhost:3000/api/bears/:bear_id` to view a bear
`PUT http://localhost:3000/api/bears/:bear_id` to update a bear
`DELETE http://localhost:3000/api/bears/:bear_id` to delete a bear


