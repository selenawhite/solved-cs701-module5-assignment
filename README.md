Download Link: https://assignmentchef.com/product/solved-cs701-module5-assignment
<br>
<strong>You are strongly encouraged to add comments into your program!</strong>

Create a new folder named HW5_<em>lastName. </em>Write the following programs in this folder. <strong>Part 1 – Angular Services (50 Points) </strong>

Using <strong>Angular services</strong>, build the Angular application to display the directions from location A to location B. The data is obtained using the MapQuest API as shown in the following link:

<u>https://developer.mapquest.com/documentation/open/directions-api/route/get/</u>

Sign up on the Mapquest developer page to get the free API key: <u>https://developer.mapquest.com</u>

The data is returned in JSON format. The following data is used in this sample:

<ul>

 <li>route.distance (Total distance)</li>

 <li>route.formatteTime (Total time)</li>

 <li>route.legs[0].maneuvers (array of Turn-by-turn directions)</li>

</ul>

From each maneuver object, use the following data:

<ul>

 <li>narrative, distance, mapUrl, and iconUrl</li>

</ul>

The initial layout of the application is shown below. The From and To fields are prepopulated. When the page is loaded, the directions are shown for those entries.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/09/733.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/09/733.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>When the user clicks the line item entry, the associated map is displayed in another window as shown below. The URL displayed is the mapUrl property.

<strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/09/226.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/09/226.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript>Also, when either the From or the To location entries change, the directions should be loaded automatically for those entries. </strong>




<strong>Part2 – Angular Routing (50 points) </strong>

Using Angular Routing and the RoutingSample2 provided in the lecture, complete the application with the appropriate routes for adding a contact, editing an existing contact, deleting an existing contact, and information about an existing contact. Adding a contact should also have the option for Cancel and Save. Editing a contact should have the option for Cancel and Save. Deleting a contact should prompt for confirmation.


