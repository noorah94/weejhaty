# client

## User story format:

- Signup: As an anon, I can sign up in the website as the user so that I have permission to add and remove my comments and add likes.
- Login: As a user, I can login to the website so that I can start to add and remove my comments and add likes.
- Logout: As a user I can logout from the website so no need to use it anymore.
- Add comment: As a user, I can start to add a comment so that I can see it on the website.
- Delete comment: As a user, I can start to remove a comment so that I can't see it on the website.
- Show my account information: As a user, I can show my info so that I can see and edit it on the website.
- Browse the trips: As a user, I can browse the trips so that I can select from them on the website.
- Browse the trending trips: As a user, I can browse the trending trips so that I can select from them on the website.
- Post a trip you took: As a user, I can post a trip you took so that I can other users can view and comment on it.
- Browse the info trip: As a user, I can show the info trip so that I can make a decision if I want to select it or not.

## Admin story format:

- Login: As an admin, I can login to the website so that I can start to add, update and remove trips.
- add trip: As an admin, I can start to add a trip so that users can see it on the website.
- update trip: As an admin, I can start to update a trip so that users can see it on the website.
- Delete trip: As an admin, I can start to remove a trip so that I can't see it on the website.
- Delete comment: As an admin, I can start to remove a comment to any user so that I can't see it on the website and the user can't see it also.
- Delete the user trip post: As an admin, I can start to remove the user trip post to any user so that I can't see it on the website and the user can't see it also.

## Design:

![image img](https://github.com/MP-Project-Noorah/client/blob/main/images/image.png)
![image2 img](https://github.com/MP-Project-Noorah/client/blob/main/images/image2.png)
![image3 img](https://github.com/MP-Project-Noorah/client/blob/main/images/image3.png)
![image4 img](https://github.com/MP-Project-Noorah/client/blob/main/images/image4.png)
![image5 img](https://github.com/MP-Project-Noorah/client/blob/main/images/image5.png)
![image6 img](https://github.com/MP-Project-Noorah/client/blob/main/images/image6.png)

## UML:

![Untitled%20Diagram.drawio img](https://github.com/noorah15/client/blob/main/Untitled%20Diagram.drawio.png)

## React Routes

| key                    | Permissions | Behavior                                                  |
| ---------------------- | ----------- | --------------------------------------------------------- |
| /                      | public      | It is showing the website description and trending trips. |
| /trips                 | public      | It shows all trips.                                       |
| /trendingTrips         | public      | It shows the trending trips.                              |
| /tripInfo/:id          | public      | It shows specific trip.                                   |
| /userTrip              | public      | It shows the user trip.                                   |
| /userTripInfo/:id      | public      | It shows the specific user trip.                          |
| /addUserTrip           | user        | It shows the specific user trip.                          |
| /signin                | public      | It allows the users to signin.                            |
| /login                 | public      | It allows the users to login.                             |
| /resetPass             | user        | It allows the users to reset password                     |
| /confirmEmail          | user        | It allows the users to confirm email                      |
| /userInfo              | user        | It allows the users to get their own info.                |
| /recordedTrips         | user        | It allows the users to get their recorded trips info.     |
| /addToRecordedTrips    | user        | It allows the users to add new trip.                      |
| /editRecordedTrip      | user        | It allows the users to edit trip.                         |
| /deleteToRecordedTrips | user        | It allows the users to delete trip.                       |
| /myFav                 | user        | It allows the users to show the user favorite trips.      |

## Links:

- [Link to server](https://github.com/MP-Project-Noorah/server)

- [Link to client](https://github.com/MP-Project-Noorah/client)

- [Link to presentation](https://www.google.com)

- [Link to Deployed App](https://www.google.com)
