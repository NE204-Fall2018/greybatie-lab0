# Overall (83/100)
 - Probably want smaller, more fine-grained commits; aids in following the 
   flow of the project as well as being able to navigate the history.

# Build (8/10)
 - Mentioning dependencies in README is good
 - You forgot to include instructions for running your analysis

# Testing (10/10)
 - Note that your `make test` command was not actually running the test 
   suite... see commit 96c84b5
 - Well-designed test for this application (though using a modulus would likely
   be more straightforward than base-two log)

# Introduction / Motivation / Background (13/15)
 - You're clearly paying attention in lecture :)
 - The scope of your introduction is quite large... I realize that this is an
   especially difficult thing to narrow-down for Lab 0, where the task is so
   trivial, but for future labs you should try to focus the introduction more
   on the specific task at hand.

# Methods (12/15)
 - Nice description of the data you will be working with
 - Missing some relevant detail in methods: how are the peak centroids to be
   determined in your analysis?

# Results and Discussion (30/40)
 - Beware of significant figures: the presented results imply a much higher 
   precision than you can have given your data.
 - As mentioned in the methods, uncertainty analysis is not necessarily 
   possible as the method for determining peak centroids is not discussed.

# Conclusion
 - Don't necessarily need a separate conclusion section: discussion can serve
   the purpose here.
 - Adequate for lab 0, but in general the conclusion should not ONLY be a 
   restatement of what you did, but a discussion of the relevant results 
   (e.g. the accuracy of the calibration) and the limitations of the 
   described methods.
