# Using APIs to Help Users Plan Vacations

### Project Overview
Using Google Maps API and Python to deliver a new product for the PlanMyTrip app. Users will be able to input a desired temperature range in order to receive a list of potential vacation spots with nearby hotels. Then, they can pick a few cities to create an itinerary.

#### Deliverable 1: Retrieving Weather Data
To begin with, 2,000 randomly generated sets of latitudes and longitudes are then passed through Google Maps API in order to retrieve the nearest city and its weather data.

![image](https://user-images.githubusercontent.com/107162310/180349486-3c1a91bc-c0bf-4d5c-b868-0013cac13fea.png)

![image](https://user-images.githubusercontent.com/107162310/180349534-b5ea1f27-d22f-4fed-b85b-272ec956546d.png)

This data is then organized into a dataframe and exported as a CSV file.

![image](https://user-images.githubusercontent.com/107162310/180349663-e83e5bc9-7ec6-486d-b581-10704a3f7175.png)

#### Deliverable 2: Creating a Customer's Travel Destinations Map
Using the CSV file from Deliverable 1, input statements are created to allow the customer to use their weather preferences to help the app identify possible vacation destinations and nearby lodging. 

![image](https://user-images.githubusercontent.com/107162310/180351149-8510449b-f4d9-4e20-ab61-ddf99f49f4bf.png)

![image](https://user-images.githubusercontent.com/107162310/180351180-f69d5154-a7fd-4443-979f-d9c60134c288.png)

![image](https://user-images.githubusercontent.com/107162310/180351271-94084693-a7ad-4b99-8f81-3a9e2fbcb0d9.png)

The hotels are then exported as another CSV file. And then, those destinations are then displayed in a marker layer map with the ability for the customer to select the pop-ups to read snippets of the destination/hotel.

![image](https://user-images.githubusercontent.com/107162310/180351399-80fd41b3-69aa-4274-87e1-70fbfed36a32.png)

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/107162310/180352443-b1a7cdb9-189c-4bcc-8668-8b08e3fd204d.png)

#### Deliverable 3: Creating a Customer's Travel Itinerary Map
Using Google Directions API, a travel itenerary map is generated that shows how to traverse between four cities from the customer's possible destinations.

![image](https://user-images.githubusercontent.com/107162310/180352211-2009be93-ac2c-46bb-8f88-fcc557e28204.png)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/107162310/180352478-a3165dd0-b1f0-424f-919a-258b025e1546.png)

Last of all, another marker layer map is generated with pop-ups for each city on the itinerary.

![image](https://user-images.githubusercontent.com/107162310/180352362-10114a44-e3b7-4b37-afc9-52164cea1e67.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/107162310/180352492-b6a39789-25a1-4551-bb01-4eb4c5364a67.png)
