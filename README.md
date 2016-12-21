# Readme

### Example curl command
`curl -X POST http://localhost:3000/posts -H "Content-Type:application/vnd.api+json" -d '{ "data": { "type": "posts", "attributes" : { "title" : "Bam", "body" : "Shabam" }, "relationships" : { "user" : {"data" : { "type" : "users", "id": "1" } } } } }'`

