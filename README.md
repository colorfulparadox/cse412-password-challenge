## Password Challenge Thing

Check step3.png for an example of it working with a hashed password
Also check step1.png of an example of it working in plaintext.


I used hashlib to hash the password:
https://docs.python.org/3/library/hashlib.html

I setup my database in a docker image to port 5430
also I named my database users


you also need flask and psycopg2 installed to run
```
pip install flask psycopg2
```