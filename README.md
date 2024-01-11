BookingAPI restful-booker > Collection on Postman > Exported to Run on Newman from cmd > HTML dashboard
Will need authorization code or token for PATCH and Delete

GET// curl -i https://restful-booker.herokuapp.com/booking

Auth//
curl -X POST \
  https://restful-booker.herokuapp.com/auth \
  -H 'Content-Type: application/json' \
  -d '{
    "username" : "admin",
    "password" : "password123"
}'
