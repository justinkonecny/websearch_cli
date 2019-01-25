# websearch
Searches/parses craigslist.org for valid vehicle listings matching user criteria.<br>
Once executed, the program prompts the user for the search model. Upon entering the model, or entering '$all', the program
beings searching craigslist.org for listings of car models that match preset criteria (price, miles, year). The search
processes listings in three different listing regions. Entering <code>$all</code> will search for all preset models (at this time, these are "mercedes", "bmw", and "wrangler"). After processing
all listings, the user will be prompted to enter commands (listed below) to interact with the results.

## User Commands
- <code>reduce</code>: eliminates duplicate listings
- <code>show all</code>: lists the age and title of all saved listings
- <code>show urls</code>: lists the search urls from which the listings are pulled
- <code>show #</code>: shows the full description of the # listing (e.g 'show 3' displays the third listing found)
- <code>expand all</code>: shows the full description of all listings
- <code>open #</code>: opens the # listing in the default web browser
- <code>open all</code>: opens all listings found in the default web browser
- <code>open search <name></code>: opens the specified search url (as listed from 'show urls') in the web browser 
- <code>remove # [#...]</code>: removes all numbered listings from the saved list (e.g. 'remove 3 5' deletes the third and fifth listings)
- <code>email all \<email\></code>: emails all results to the specified email address (provided credentials are stored in send_mail())
- <code>exit</code> or <code>quit</code>: terminates the program
