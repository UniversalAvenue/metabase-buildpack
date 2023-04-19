# Heroku Buildpack for Metabase

Add the following to your app.json:

```
"buildpacks": [
  {
    "url": "https://github.com/metabase/metabase-buildpack"
  }
]
```

## Update new Metabase version
1. Navigate to `bin\version` and click edit 
2. Update the version 
3. Fill out commit changes and submit changes
4. Navigate to heroku
5. Select the Metabase project
6. Navigate to deoploy tab
7. Click deploy
