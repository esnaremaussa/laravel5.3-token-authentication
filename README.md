#Simple token based authentication

After installation go to tinker and create users:<br>
factory('App\User')->create();

Then try this in Postman:<br>
http://localhost:8000/api/user?api_token="The token key"

More info:<br>
https://laracasts.com/series/whats-new-in-laravel-5-2/episodes/5
