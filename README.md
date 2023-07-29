# spotifynd-docs
Documentation for Spotifynd

Before running the project locally, you have to - 
## Get your spotify API credentials  
- Log on to [Spotify Dashboard](https://developer.spotify.com/dashboard/)
- Create a new app. This should generate CLIENT_ID and CLIENT_SECRET
- Copy and paste these into your local copy of [creds.py](https://github.com/absotone/spotifynd/blob/main/creds.py)

## Instructions to run the project
- Navigate to the directory
-   ```pip install pipenv```
-   ```pipenv check```
-    ```pipenv install```
-    ```pipenv shell```
-    ```python app.py```

## Get a song ID from spotify
- Right-click on the track on the Spotify app and click on `Share>Copy Song Link`
  - This would return a link like `https://open.spotify.com/track/748mdHapucXQri7IAO8yFK?si=d7f32a55ef7e42cd` 
    - The ID will hence be `748mdHapucXQri7IAO8yFK?si=d7f32a55ef7e42cd`


