# Simple token based authentication

<p>After installation go to tinker and create users:<br>
factory('App\User')->create();
</p>

<p>
Then try this in Postman:<br>
http://localhost:8000/api/user?api_token="The token key"
</p>
