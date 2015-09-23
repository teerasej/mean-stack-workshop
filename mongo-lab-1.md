# Mongo Shell
1. mongod.exe --dbpath "c:\data"
2. use dbname
3. db.users
4. db.users.insert( { username:'teerasej' , email:'teerasej@nextflow.in.th' });
5. db.users.find();
6. add more user document
7. db.users.find({ username: 'teerasej' });
8. db.users.update( { username: 'tony' }, { $set: { email:'stark@gmail.com' } } );
9. db.users.remove( { username: 'steve' } );
10. db.users.drop();
