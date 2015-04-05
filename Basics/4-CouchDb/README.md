## Basics
	* Key/ Value concept
	* CAP theorem
		* What does C, A, P really mean? 
	* Why does CouchDB make sense for Artoo?
	* What are design docs?

## Document API
	* API
	* Differences between docs, local docs, and _design/docs?

## Map Reduce
[What is Map Reduce?](http://stevekrenzel.com/finding-friends-with-mapreduce)

## Views
	* How does Map, Reduce really work?
	* Key structure
	* View Options
		* Local Sequence

## Changes
	* How does changes work?
	* API structure?
	* Create a DB and a few docs. Demonstrate the effect of the following query params:
		* since
		* feed
		* filter

## Replication
	* What's the point of replication?
	* How does one do filtered replication?

## Extra
	* What are Show / List / Update APIs?

## Tasks
	* Using `curl`, create 2 databases, add 5 different documents in each. Create a third which contains 10 combined. Build a view to display the different sets of docs
	* Using `curl`, create a database for 10 cricket teams/football teams/racers over 20 games with their details. Now using views:
		* Build a championship table for the team
		* Build a championship table for players
		* Build a historical view a player
		* If you had to purchase a player, which one will it be? Using a view justify your response.
	* Demonstrate Show, List and Update APIs on your dataset above
