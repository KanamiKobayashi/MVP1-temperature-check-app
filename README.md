# MVP_2
This health check app is for kids cheerleading team in Japan filling in COVID forms.

Due to COVID situation, they must check in all players' temperature for 2 weeks before attending the competition. I am developing this app to allow them save time (instead of manual recording way) and focus on practice their performance.

This app users are the parents of players and the coaches working for Japanese cheerleading association.


This is MVP_2 version. (in progress)
Main goals
1. Using Auth0 for log in, instead of flask log in. (Using Line and google)
2. Use registered database info to show user's name and information on the admin table
3. Automation from database into excel(csv) form which is provided by association.

App demos:
First you will be logged in as "Izumi" and this is the only admin who is able to visit admin page. (pass:3333)
Once you logged out and register yourself, then try to log in. You will be a new user and be able to view only submit page.


demo MVP1(English): https://temperaturecheckappmvp1en.herokuapp.com/

demo MVP1(Japanese): https://temperaturecheckapp2.herokuapp.com/
