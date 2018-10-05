# Weather_API_2018_Php

4. If $tokenInfo['access_token'] is returned, we add access_token to array $params[], then we use CURL to address {https://www.googleapis.com/oauth2/v1/userinfo} + updated $params[](that now includes access_token $_GET['code'] + Client ID, secret, redirection URI) 
