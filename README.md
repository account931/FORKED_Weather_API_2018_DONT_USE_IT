# Weather_API_2018_Php

3. If $_GET['code'] is isset, we add $_GET['code'] to array $params[], then php uses CURL to address new URL {https://accounts.google.com/o/oauth2/token} + updated $params[] (that now contains $_GET['code'] + Client ID, secret,
