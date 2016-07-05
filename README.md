Dr Pepper needs your help
=========================

Dr Pepper has asked for your help in designing his company's infrastructure. He would like to move their infrastructure off of their self-hosted Toshiba tablets and into the cloud, but he doesn't have any idea where to start. You'll need to explain to him the what the buzzwords mean, and come up with a solution for their new infrastructure.

Dr Pepper's grandson's girlfriend's uncle built a monolithic PHP application with SQLite and Riak databases. It works well, but reliability has been a problem. Also, Dr Pepper has heard of all the hackers out there who might be trying to hack his servers. This is a serious concern for the company because their drink formula is top secret. Were this formula to be leaked, Dr Pepper's business would collapse.

Task 1
------

Please create a private github repository to contain your work and grant coen.hyde@gmail.com read access to the repository.

Task 2
------

Design Dr Pepper's new infrastructure for AWS to be resilient to failure and highly secure. For the moment, it is not feasible to redesign the application, but they are open for suggestions for modifications once the initial migration is complete. Please explain to Dr Pepper in simple English terms what technology you will use. Dr Pepper's grandson's girlfriend's uncle will also be reviewing the designs. He likes to go deep on the technical details.

Task 3
------

Dr Pepper has a hobby collecting cars and has asked you to write a Bash script to process all car models from http://www.carqueryapi.com/api/0.3/?cmd=getMakes and upload the result to Amazon S3. He would like the cars grouped by country and sorted in descending order by name. He would also like to know how many cars have been released for each country. Dr Pepper's grandson's girlfriend's uncle mentioned something about `jq`.

Upload the result to s3://bucket/{first_name}-{last_name}.json with the credentials you have been granted.
