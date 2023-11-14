##### Get Profile
```.js
const profile = await fetch("/get/profile/omermujtaba");
```
##### Response

```.json
{
    "name": "Omer Mujtaba",
    "location": "Vaughan, Ontario",
    "profession": "Software Engineer",
    "experience": [
        {
            "company": "Zendesk",
            "title": "Software Engineer II",
            "startDate": "Jan, 2022",
            "endDate": "Present",
            "current" : true,
        },
        {
            "company": "Morangofilms",
            "title": "Full Stack Engineer",
            "startDate": "May, 2020",
            "endDate": "Jan, 2022",
        },
        {
            "company": "Switch - Ideas That Connect",
            "title": "Software Engineer",
            "startDate": "Jul, 2018",
            "endDate": "Nov, 2019",
        },
    ],
}

```

