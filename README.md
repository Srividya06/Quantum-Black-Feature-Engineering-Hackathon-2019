# Quantum-Black-Feature-Engineering-Hackathon-2019

Problem Statement


ACRTA road taxation data engineering

Astro City Road transport authority (ACRTA) in US have come up with an idea to use car registration renewal charges to provide indirect incentives to safe drivers. Also, providing subsidies to certain areas as per the extreme climatic conditions in terms of heavy snow or rain.

Develop inputs for a model that predicts the chances of having a vehicle accident based on driving conditions. This model will help the transport authority to understand risk patterns and act upon them.

This output then would be utilized so as to come up for a risk-based taxation on different drivers and locations as per crash-prone weather conditions.

Use cases would be –

Imposing “unsafe driving tax” on drivers to provide a positive feedback loop which may be revisited every year by looking at the past year trip data based on the driving patterns. Lower the tax in the regions where the climatic conditions lead them to become a crash-prone site.

Data Description

1. Drive Data (Connected car data) — Data coming from the car-mounted devices, which provides you with the car statistics every second. This information will include — Speed, acceleration, engine temperature and other car statistics.

2. Trip — Parameters associated with location of car such as lattitude, longitude, altitude and other similar parameters

3. Weather — Weather condition at different latitude & longitude during different times each day.

4. Vehicle Specifications — Different vehicle technical specifications which comes from the manufacturer of the car.


To Create

1. Engine Features (engine_features.csv)
2. Drive Features (drive_features.csv)
3. Weather Features (weather_features.csv)

Assumptions & Hints–

Hint: convert time zone to PST before any calculations

Weather data is already in PST and may not need any timezone conversion. You may consider the weather data to be constant for complete hour basis. For example- if the temperature is given to be 284.51 for 2017-02-14 19:00:00, it would be the same for time 2017-02-14 19:15:45 as well. Haversine formula must be utilized to measure the distance between any 2 consecutive points in between the trips. Matches in between datasets must be on geohash precision point 5.

Studies have found that - The haversine formula determines the great-circle distance between two points on a sphere given their longitudes and latitudes. Important in navigation, it is a special case of a more general formula in spherical trigonometry, the law of haversines, that relates the sides and angles of spherical triangles.

Code

Not a complete code. Weather data still not done

Rank Obtained
89




