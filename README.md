# Unofficial Glitch API Docs
Welcome to unofficial Glitch API Documentation! 
This github is for updating the [methods](https://github.com/TurboBiscuit/glitch-api-docs/)
If you have any methods you've found make a pull request with the modified JSON file

## Method Object
```jsonc
{
    "method": "GET", //Can be any of the HTTP Methods
    "path": "/path/of/endpoint/excluding/version",
    "name": "Name of enpoint",
    "description": "Description of endpoint",
    "endpoint_version": "1", //1 is https://api.glitch.com/ , 2 is https://api.glitch.com/v1/
    "query": [{
        "optional": true, //true or false
        "name": "queryKey",
        "description": "Description of what the query does."
    }],
    "headers": [{
        "optional": false, //true or false
        "name": "Header-Key",
        "description": "What this header does or is."
    }],
    "example": "https://api.glitch.com/path/to/endpoint/including/version"
}
```
