# my-scripts
Saving my scripts

## Postman: Save access token to environment when logging in

```
pm.environment.set('API_ACCESS_TOKEN', pm.response.headers.get('Authorization'));
```
