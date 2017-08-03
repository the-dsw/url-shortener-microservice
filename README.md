
# FreeCodeCamp API Basejump: URL Shortener Microservice
## User stories:
1. I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
2. If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.
3. When I visit that shortened URL, it will redirect me to my original link.

## Example creation usage:

```js
https://new/https://www.google.com
https://new/http://freecodecamp.com/news
```

## Example creation output:

```js
{ "original_url": "http://freecodecamp.com/news", "short_url": "BkbxmFxPW" }
```

## Usage:

`http://localhost:3000/BkbxmFxPW`

### Will redirect to:

`http://freecodecamp.com/news`
