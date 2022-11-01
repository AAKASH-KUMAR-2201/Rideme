# Rideme

1. Create a virtual env and `pip install -r requirements.txt`
2. Run the app with `python run.py` or `python3 run.py`
3. Checkout the endpoints and test them with a tool like [POSTMAN](https://www.getpostman.com)

## API ENDPOINTS

EndPoint | Functionality
-- | --
POST `/api/v1/rides` | Creates a new ride
GET `/api/v1/rides` | Fetches all available rides
GET `/api/v1/rides/<ride_id>` | Fetches a single ride
POST `/api/v1/auth/rides/<ride_id>/requests` | Creates a ride request
