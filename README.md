# websearch
Searches/parses craigslist.org for valid vehicle listings matching user criteria.<br>
Once executed, the program prompts the user for the search model. Upon entering the model, or entering '$all', the program
beings searching craigslist.org for listings of car models that match preset criteria (price, miles, year). The search
processes listings in three different listing regions. Entering <code>$all</code> will search for all preset models (at this time, these are "mercedes", "bmw", and "wrangler"). After processing
all listings, the user will be prompted to enter commands (listed below) to interact with the results.

## User Commands
- 'reduce': eliminates duplicate listings
- 'show all': lists the age and title of all saved listings
- 'show urls': lists the search urls from which the listings are pulled
- 'show #': shows the full description of the # listing (e.g 'show 3' displays the third listing found)
- 'expand all': shows the full description of all listings
- 'open #': opens the # listing in the default web browser
- 'open all': opens all listings found in the default web browser
- 'open search <name>': opens the specified search url (as listed from 'show urls') in the web browser 
- 'remove # [#...]': removes all numbered listings from the saved list (e.g. 'remove 3 5' deletes the third and fifth listings)
- 'email all <email>': emails all results to the specified email address (provided credentials are stored in send_mail())
- 'exit' or 'quit': terminates the program
