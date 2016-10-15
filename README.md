# laravel5.3-token-authentication
Simple token based authentication

After installation go to tinker and create users:
factory('App\User')->create();

Then try this in Postman:
http://localhost:8000/api/user?api_token="The token key"
