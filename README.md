# redditbot
a Daniel Plainview themed auto reply redditbot
Small comment reply bot based on PRAW. 
This script will scan the comments of a subreddit as they come in and look for a trigger word. 
If a comment contains the trigger word, the script will reply with a random quote from quote.txt. 
Further, if the random quote that has been selected contains !USERNAME, the script will replace !USERNAME with the author of the comment it is replying to. 
The quotes should be placed in a text file called quotes.txt, and each quote should be placed on its own line.
