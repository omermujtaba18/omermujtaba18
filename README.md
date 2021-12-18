##### Get Profile
```.js
const profile = await fetch('/get/profile/omermujtaba');
```
##### Response

```.json
{
  "name": "Omer Mujtaba",
  "location": "Montreal, Quebec",
  "profession": "Software Engineer",
  "technology_stack": [
    "node-js",
    "javascript",
    "typescript",
    "react",
    "react-native",
    "php",
    "python",
    "MongoDB",
    "MySQL",
    "git",
    "bootstrap",
    "html",
    "css"
  ],
  "learning": [
    { "current" : [ "typescript:advance", "node-js:advance" ] },
    { "future" : [ "unit-testing:advance", "docker", "kubernetes", "RabitMQ", "Redis", "AWS", "GCP" ] }
  ] 
}
```

