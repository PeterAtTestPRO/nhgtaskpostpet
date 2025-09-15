Begeleidende informatie.

I have created for both 'Pet' en 'User' four API calls. GET, POST, PUT and DELETE.
They all have a "baseUrl". 'Pet' has a common "petId". 'User' has a common "userName".

The testing of the API is simple. 

1. Do a GET: No results. Result is a 404 (Not Found)
2. Do a POST: Info added to table of the database. Result is a 200 (OK)
3. Do a GET: Info stored in table of the database. Result is a 200 (OK)
4. Do a PUT: Info updated in table of the database. Result is a 200 (OK)
5. Do a GET: Updated info stored in table of the database. Result is a 200 (OK)
6. Do a DELETE: Info removed from table of the database. Result is a 200 (OK)
7. Do a GET: No results. Result is a 404 (Not Found)


To be done:
- Add protection means of credentials to each requext (Bearer token e.g.)

