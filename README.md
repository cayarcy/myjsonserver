# myjsonserver
serveur de test en json private
Permet d'interroger en REST un server de simulation equivalent à :

https://jsonplaceholder.typicode.com/
https://my-json-server.typicode.com/

Contient un fichier db.json:
{
  "posts": [
    {
      "id": 1,
      "title": "Post 1"
    },
    {
      "id": 2,
      "title": "Post 2"
    },
    {
      "id": 3,
      "title": "Post 3"
    }
  ],
  "comments": [
    {
      "id": 1,
      "body": "some comment",
      "postId": 1
    },
    {
      "id": 2,
      "body": "some comment",
      "postId": 1
    }
  ],
  "profile": {
    "name": "typicode"
  }
}
