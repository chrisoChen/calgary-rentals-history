# calgary-rentals-history

A git scraper to track changes made to the calgary short term rentals API.

# To Use

A Github Action's workflow file runs on a CRON schedule and makes a GET request to a HTTP endpoint. It then serializes the data into a file and compares it to Git.

If there are file differences, it will commit the file into the repo and push.
