# Mood-sensing-app
A back-end implementation for facial emotion sensing using AWS Rekognition REST API. This project is based on Django REST framework and has three main functions: 1) Upload a mood capture for a given user and location (POST request to http://localhost/api/Mood/ you must include  your user credentials, Latitud, Longitud, Photo (imageFLocalFile) it will be record the timestap and   consume AWS Rekognition service to determine your facial emotion) 2) Return the mood frequency distribution for a given user (GET request to http://localhost/api/Mood/ with your user credentials to verify your mood stats. Also you can use http://localhost/user/stats/?userid= to know other user stats for which you need admin access.) 3) Return the proximity to locations (home, office, shopping center,…) where a given user is happy. (Using the http://localhost/happyplaces/?userid= GET request)
