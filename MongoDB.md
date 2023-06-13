init DB: service mongodb start, status stop

2. Run mongosh
test> show dbs
create DB 'test_db'        : use test_db
show all collection in DB  : show collections
delete DB                  : db.dropDatabase()
insert record in db        : db.products.insertOne({name: "Coffee mug", description: "Coffee is necessary for coder, best mug for it", price: 9.99})


## Mongoose setup

1: npm init --y to set up that package.json file.
2: npm install mongoose