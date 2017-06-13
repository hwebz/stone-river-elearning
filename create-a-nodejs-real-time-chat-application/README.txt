mongod                      - to start mongodb server
mongo                       - to test chat db
    use chat
    db.messages
    db.messages.find()
    db.messages.remove()
node server.js              - to start socket.io server
http-server . -p 3500 -c-1  - to start local server