# Solution for User and Article Performance Data Assignment

## Steps in the process

* Fetchng files from s3 and loading to Dataframe
* Splitting data into vies and article info Dataframes
* Article and User performance calculations in Daraframes
* Aticle Performance table creation & data insertion
* Get inserted records
* User Performance table creation & data insertion
* Get inserted records

## Observations

> * Articles with single ID are having multiple names/categories. In my opinion, Each article must be associated with a single name & category.
> * There are some articles which have been marked as article_viewed by a particular user, but doesn't have a card_view with that user

## Steps to execute tests

* Start the container etl-1
* Open the etl-1 container in a terminal
* Under the /app directory, enter the command 
`pytest`
* This will execute 2 tests present under tests folder. These tests validate the logic on a smaller data set.
