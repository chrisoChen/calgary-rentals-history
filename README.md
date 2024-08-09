# calgary-rentals-history

A git scraper to track changes made to the Calgary Short Term Rentals API.

# To Use

A Github Action's workflow file runs on a CRON schedule and makes a GET request to a HTTP endpoint. It then serializes the data into a file and compares file differences using Git.

If there are file differences, the file will be commited into the remote repo.
