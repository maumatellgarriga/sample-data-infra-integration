FROM mongo:4.1-xenial

COPY reviews.json /reviews.json
CMD mongoimport --host mongodb --db source --collection reviews --type json --file /reviews.json