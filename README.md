# MU2022-OnlineTickets
## Description
Online Tickets is an app that buy/sell tickets for entertainment places such as theaters, concerts, museum , .etc. For individual user, they can search tickets from app, and buy tickets. For the tickets provider, they can edit ticket information, upload new tickets. 

## App evaluation

- Mobile: Ticket buyers could see locations of entertainment places and see tickets availability in real time, which are features make mobile app more than a website
- Story: By purchasing tickets in advance, ticket buyers can avoid time wasting when waiting for tickets in person, and ticket sellers can manage their ticket resources
- Market: Everyone can use this app to buy the tickets, any entertainment provider could upload their tickets
- Habit: For provider, I think they will use frequently to upload their available tickets. For individual user, they will use sometimes/often when hanging out with friends/family.
- Scope: Technically challenge is beside letting providers upload tickets themselves, the app also call api to get the ticket availability in real time. An there are many API from many theaters, concerts, museums.

## Product Spec
1. User stories
**Must-have**
- ticket category: theaters, concerts, museum
- individual user login, logout
- individual user can search tickets, buy tickets
- individual user can see tickets availability in real time
- individual user can see locations of entertainment places
- ticket provider login, logout
- ticket provider can edit existing tickets
- ticket provider can add new tickets
- handle privacy for credit card info

**Nice-to-have**
- individual user can see the bought ticket history
- ticket provier can check the tickets history
- individual user can accumulate bonus points for purchasing tickets many times
- auto-suggestion on entertainment places based on user's history

2. Screen Archetypes
- Login: both tickets buyer and seller log in
- register: both tickets buyer and seller sign up
- search ticket: it will show the current tickets that are available by default and auto-suggestion places, users can search for their desired tickets
- ticket buying: (buyers will be prompted to fill in information on name, phone number, and card info after sign up) buyers review their purchase information and tap to buy.
- ticket uploading: sellers upload their tickets
- tickets history: buyers see their ticket history and their accumulated points/bonus

3. Navigation
**Tab Navigation **(Tab to Screen)
- Search tab
- Profile tab 
- Location tab

**Flow Navigation**
- Log in screen => Search/Sugestion screen
- Sign up screen => Information filling screen
- Search/Sugestion screen 
=> Buy tickets screen (when add to cart button is clicked)
=> My profile screen (when profile icon is clicked)
- Location screen => Buy tickets screen (when icon pinned on map is clicked)

## Wireframe 
Updating
