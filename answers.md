### Keywords and Reponses (In place for the table in the student guide)
* "who" --> "You tell me who that is."
* "life" --> "Life sucks."
* "robot" --> "Hey, don't use the r-word!"  

When more than 1 keyword is included in a string, the first keyword that appears is the response that is sent. In order to prioritize repsonses in the reply method, the if/else if statements need to be changed.
  
1. What happens when a keyword is included in another word? Consider statements like "I know all the state capitals" and "I like vegetables smothered in cheese." Explain the problem with the responses to these statements.
    * The word "know" contains "no" so the code will respond with "Why so negative?" even though the user never directly said the word "no". The same goes with "smothered" as it contains "mother".