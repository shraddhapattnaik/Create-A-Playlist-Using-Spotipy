# Create A Playlist Based On Featured Playlists
*A Project by Shraddha Pattnaik*

### Steps done to create a playlist:
1. Import necessary libraries
2. Provide your client id, client secret and redirect uri
3. Authorization and get token
4. Data Extraction:
    a. User's top tracks
    b. Featured Playlists
5. Fetch audio features of the tracks
6. Analyze the features using Random Forest Regressor
7. Make a playlist using top 2-3 featured playlists closest to user's top tracks 
8. Create a new playlist and add the songs
