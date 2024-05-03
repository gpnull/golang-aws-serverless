# golang-aws-serverless

curl --header "Content-Type: application/json" --request POST --data '{"email": "gpdev1705@gmail.com", "firstname": "giang", "lastname": "pham"}' https://xxxxx.execute-api.xxxx.amazonaws.com/staging

curl -X GET https://xxxxx.execute-api.xxxx.amazonaws.com/staging

curl -X GET https://xxxxx.execute-api.xxxx.amazonaws.com/staging\?email\=gpdev1705@gmail.com

curl --header "Content-Type: application/json" --request PUT --data '{"email": "gpdev1705@gmail.com", "firstname": "giangg", "lastname": "phamm"}' https://xxxxx.execute-api.xxxx.amazonaws.com/staging