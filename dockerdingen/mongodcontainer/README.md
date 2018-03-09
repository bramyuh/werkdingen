docker container run --name dockermongo -d -v /var/lib/mongodb/:/data/db -p 27017:27017 --restart always  mymongo
