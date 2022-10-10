
# Redis

Redis is an in-memory data structure store, used as a distributed, in-memory key–value database, cache and message broker, with optional durability.

In this repo redis is used to test the response time reduction of request.
On first request it takes time in normal manner but after using redis response time decreases significantly.

## API Reference

#### Get all weather information


http://www.7timer.info/bin/api.pl?lon=113.17&lat=23.09&product=astro&output=json


## Screenshots

### Normal data request

![Normal](https://raw.githubusercontent.com/thisisrahulpal/redis/main/screenshots/Without%20Redis.png)

### After using redis

![After Redis](https://raw.githubusercontent.com/thisisrahulpal/redis/main/screenshots/with%20Redis.png)
