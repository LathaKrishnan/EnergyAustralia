
Demo:

https://energyaustraliamusicfestival.herokuapp.com/

Music Festival  for EnergyAustralia Coding Test
This is simple program in respond to EnergyAustralia coding test, which request data from swagger API and then parse into a  particular manner: at the top level, it should show the band record label, below that it should list out all bands under their management, and below that it should display which festivals they've attended, if any. All entries should be sorted alphabetically.

For example:

Record Label 1
Band X
Omega Festival
Band Y
Record Label 2
Band A
Alpha Festival
Beta Festival

Technologies used
Ruby

Gems used:
pry
sinatra
sinatra/reloader
httparty

Solved issue

1. swagger API sometime return response code 429 and cause the program exit in error
2. response data from swagger API sometime is missing few chunk of data which may crashing my site

Have worked out how to better handle errors caused the API responding with an empty array or with a 429 code. Individual messages are now being displayed. I used giphy.com  gif to show the error message to make the website looks better.

I concentrated on CSS as a main thing once I made my Data to display.

Author
Latha Krishna 