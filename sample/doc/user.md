## <a name="resource-user">User</a>

Stability: `prototype`

User API

### Attributes

| Name | Type | Description | Example |
| ------- | ------- | ------- | ------- |
| **id** | *integer* | unique identifier of user | `1` |
| **mail** | *string* | unique user email | `"otyoppu@example.com"` |
| **name** | *string* | user Name | `"otyoppu"` |

### User Info

Info for existing user.

```
GET /users/{user_id}
```


#### Curl Example

```bash
$ curl -n /users/$USER_ID
```


#### Response Example

```
HTTP/1.1 200 OK
```

```json
{
  "id": 1,
  "name": "otyoppu",
  "mail": "otyoppu@example.com"
}
```


