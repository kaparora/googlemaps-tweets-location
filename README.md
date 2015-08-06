# googlemaps-tweets-location
HTML , Javascript to show google maps with tweet locations and text 

Using this program you can show where are people tweeting about something and then click on the markers and see the tweet.



We will fetch data to trace on map using the app from github repo: https://github.com/kapilarora/twitter-api-ruby

When we run this we can use this java script to fetch the twitter location and tweet data for netapp.

We will parse this data and trace on the map

You can update the below  url to fetch data for some other hashtag

"http://localhost:9292/locandtweet/netapp"

e.g. 
"http://localhost:9292/locandtweet/deutschebahn"


Currently map markers have netapp log:
Which can be changed by updating this image property:
var image = {
    url: 'http://community.netapp.com/html/rank_icons/employee-logo.png',
    // This marker is 20 pixels wide by 32 pixels tall.
    size: new google.maps.Size(13, 11),
    // The origin for this image is 0,0.
    origin: new google.maps.Point(0,0),
    // The anchor for this image is the base of the flagpole at 0,32.
    anchor: new google.maps.Point(7, 11)
  };