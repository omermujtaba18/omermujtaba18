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
  "dev_stack": [
    "node-js", "typescript", "javascript", "MongoDB",  "react", "MySQL",  "git", 
    "react-native", "php", "python", "bootstrap", "html", "css", "Datadog"
  ],
  "learning": {
    "current" : [ "typescript:advance", "node-js:advance" ],
    "future" : [ "unit-testing:advance", "docker", "kubernetes", "RabitMQ", "Redis", "AWS", "GCP" ]
  } 
}
```

