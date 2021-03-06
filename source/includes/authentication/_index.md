# Authentication

> To authorize, use this code:

```shell
## Login
curl -X "POST" "http://localhost:3000/login" \
     -H 'Content-Type: application/json' \
     -d $'{
  "user": {
    "email": "cory+super_admin@me.com",
    "password": "Test1234!"
  }
}'
```

> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>