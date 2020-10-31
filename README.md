# Flightplan - [Link](https://sdaniels6363.github.io/bootcamp-project-1)

<u>Contributors:</u>
- Atif Rabbani
- Greg Desmarais
- John Carver
- Scott Daniels

<u>Technologies Used:</u>
- Materialize for CSS
- Tablesorter.js
- Jquery
- Google Icons and Fonts api
- SkyScanner API
- Eventbrite API
- Heroku CORS-proxy

<u>Project Summary:</u>

The goal of the project was to create a website that will find the cheapest flight from the user's origin, to their destination, as well as finding events in the area of their destination for the duration of their trip.

The SkyScanner API is the API that was used to determine the cheapest flight from the origin to the destination, with the departing flight being set on the user provided start date, and the return flight being set on the user provided end date.  

Once the submit button is selected, an additional API call is then made to Eventbrite to retrieve events taking place during the  duration of the user's trip, in the destination city that they provided.  50 events are returned containing a varitety of categories, if the user wishes to see more events, they can click the "Check For More Events" button.  This will perform an additional API call to Eventbrite for the next 50 events.  

