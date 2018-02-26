# documentdb-postman-collection
Postman collection demonstrating REST access for DocumentDB

Every script in the collection uses a pre-request script to create the AUTH headers and format the request based on simply the URL, the functions in all of the requests are actually identical, so you can copy any request, change the uri and save again and it 

## Installation
From postman simply import the collection and the environment, add your access key and document db host in the collection and you're all set, you can use the scripts to create the initial database, then the collection and documents etc.

## Changes from the original repo
I have added a new function which will enable you to use environmental variables to store database and collection names.
The standalone function can be found in this <a href="https://gist.github.com/mashariqk/62fdf2a0d6497b88ab62428021196aec">gist</a>
