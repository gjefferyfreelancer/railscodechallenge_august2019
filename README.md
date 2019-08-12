# Rails Code Challenge - August 2019

# Challenge
Your company has just acquired a new company and needs to import their data. Unfortunately, the acquired company has never stored their data in a database and instead uses a plain text file. Create a web-based application that fulfills the following requirements:

- Accepts (via a form) a tab delimited file with the following columns: purchaser name, item description, item price, purchase count, merchant address, merchant name. Assume the columns will always be in that order, that there will always be data in each column, and that there will always be a header line. An example input file named example_input.tab is included in this repo.
- Parses input file, normalizes the data, and stores the information in a relational database.
- After upload, displays the total amount gross revenue represented by the uploaded file.

The application does not need to:

- handle authentication or authorization (bonus points if it does, extra bonus points if authentication is via OpenID)
- be aesthetically pleasing

# Evaluation
Evaluation of your submission will be based on the following criteria:

- Did your application fulfill the basic requirements?
- Did you document the method for setting up and running your application?
- Did you follow the instructions for submission?
- Did you consider what changes would need to be made for a true production-ready solution? You can include your thoughts in the README.
