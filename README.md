# StudyGenie
A study genie to help students understand programming.

# Text book for our Genie:
## Primary : 
	Introduction to Programming Using Java, Seventh Edition
	http://math.hws.edu/javanotes/
	This website is more elaborate than wiki, So I think this should be the course textbook. Moreover, they have also given zip files of their website. But, we still need to crawl the content so as to split the content at much finer level.
## Recommended Reading:
	Java programming wiki that we used in Assignment 2. 
	We can provide links from this wiki as recommended links for the student when he/she is entering notes for a particular chapter/section eg: Arrays, LinkedList.

# Technology
## Spring MVC
	Spring MVC seems to be a good option because Abhishek has experience on it from Infy and Rohit from SS course.
	I setup a simple HelloWorld using Spring MVC and Maven on my machine yesterday, to start with.
## Apache Lucene
	No question on this.

# Individual Tasks
## Abhishek (The architecture guy)
	1. Create a private repo on gitlab or bitbucket.
	2. Setup the SpringMVC environment with Maven.
	3. Think of our system at a high level - What controllers, views etc. will be required to begin with. Create those to begin with. We can discuss this in person if required.
	4. Setup log4j for logging.
## Rohit (The UI guy)
	1. You can presently work in isolation on the UI theme (look and feel) (which is consistent through out the system).
	2. User login in the system (Student/Teacher/Admin). Presently don't worry about the database, we can work on it next week.
	3. UI mechanism to add/remove/drag/resize notes on the web page.
	4. Provision to drag/drop code blocks in the notes. (for loop, while, if-else block)
	5. Design the UI in way that we can easily track the user activity at the notes -> point level. (At a level of every point of a note). By user activity I mean, as and when the student types, we should be able to query Lucene with details like what chapter it belongs to, what is the current sentence the user is typing to provide auto suggests etc.)
## Vignesh
	1. Crawl and organize the content which will be most effective for Lucene Indexing.
	2. Explore Lucene for different features that might be useful for our system. (Stemming etc.)
	3. Write a function that returns an array of top N suggests for a query. (Autosuggests)
	4. Use case diagram for reference.

