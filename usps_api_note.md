### Profile Details
Name: Eugene Ku<br>
Username: copeugeneku2007<br>
Email: eugeneku2007@gmail.com<br>

Timezone: America/Chicago<br>
Crid: 51223925<br>
Custreg_uid: 445290884<br>

MyTestApp:<br>
https://developers.usps.com/user/13591/apps/mytestapp<br>

Consumer Key (username): <br>
PG28G7RV9bMTTb52APgg7H96euRjojbJhrpI6wGSpNEIJAGZ

Consumer Secret (password): <br>
ENdIT9R658phiHUQDSGU9Mlx8qEfLlKPQdQ2QFj0CDotwZDyqK5AZhmGdjDfbG76

—--------------

OAuth 2.0 Portal:<br>
https://developers.usps.com/Oauth

Payments 3.0:<br>
https://developers.usps.com/paymentsv3

API TEMP Environment:<br>
https://apis-tem.usps.com/

API Prod Environment:<br>
https://apis.usps.com

USPS APIs Cloud Enrollment:<br>
https://developers.usps.com/sites/default/files/2024-10/USPS%20API%20Cloud%20Enrollment.pdf

Eugene credential<br>
```
curl --location 'https://apis.usps.com/oauth2/v3/token' \
--header 'Content-Type: application/json' \
--data '{
    "client_id": "PG28G7RV9bMTTb52APgg7H96euRjojbJhrpI6wGSpNEIJAGZ",
    "client_secret": "ENdIT9R658phiHUQDSGU9Mlx8qEfLlKPQdQ2QFj0CDotwZDyqK5AZhmGdjDfbG76",
    "grant_type": "client_credentials"
}'
```
