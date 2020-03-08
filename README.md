# TestApi
Created Api using Flask(python)+firebase(Realtime Database)

To Access Api-
There are three routes in this Api 
(1) unprotected 
(2) Protected
(3)Login
All are using 'GET' Method
Note:here localhosturl is nothing but url of your local PC.

When user enter link:
Localhosturl/unprotected

'Anyone can see this' will be printed because that data is open source no need of anything.
When user enter link:

Localhosturl/login

A login popup will be shown .In that user will enter his credentials
With password= 'password'
user id will be anything.

Then user will get a token . Copy that token.

Localhosturl/protected?token=token
Here token is  given token after login route





