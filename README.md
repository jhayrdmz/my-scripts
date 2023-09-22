# my-scripts
Saving my scripts

## Postman: Save access token to environment when logging in

```
# Getting token from header
pm.environment.set('API_ACCESS_TOKEN', pm.response.headers.get('Authorization'));

# Getting token from response
pm.environment.set('API_ACCESS_TOKEN', pm.response.json()['data']['meta']['token']);
```
