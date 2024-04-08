
* Create a DataBase called EventDataSpring using mysql database
* In this particular path --> EventManagement_SpringProject/src/main/resources/ applicaion.properties
   In that particular file:
      Change the database password according to your database (in place of admin@123).

There are two modules in it :  user modle and admin module:
  you can use anything as the user login and registration .
  Bu, make sure to use the admin@gmail.com as email and 88888888 as the password while registering the user and try to login using the same credential so that the admin module wll the opening with this particular credentials only..
Run the application as SprringBoot Application.

after succesfully running the application
* execute this query in the database for the dynamic fetching of Event data from database- (This is must and should other wise you can't boook the events)

INSERT INTO `EventDataSpring`.`events_entity` (`event_id`, `event_amount`, `event_category`, `event_details`, `event_img1`, `event_img2`, `event_img3`, `event_name`) VALUES ('1', '85000', 'Birthday', 'Birthday event Data', 'Birthday8.jpg', 'Birthday2.jpg', 'Birthday3.jpeg', 'Birthday');


INSERT INTO `EventDataSpring`.`events_entity` (`event_id`, `event_amount`, `event_category`, `event_details`, `event_img1`, `event_img2`, `event_img3`, `event_name`) VALUES ('2', '75000', 'Marriage', 'Wedding event Data', 'wedding.jpeg', 'wedding2.jpg', 'wedding3.jpeg', 'Wedding');
