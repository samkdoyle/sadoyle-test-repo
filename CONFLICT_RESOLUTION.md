I first edited line 6 of helloworld.txt on branch 1, then when I merged that into main I had a conflict because I had already used branch2 to add lines 6 and 7 with different text

I accepted the incoming branch1 change, but then got stuck on "Git: you need to resolve your current index first" error, I had to stage the change (not just accept) it to be able to commit and have branch1 line reflect

Then I edited line6 of helloworld.txt in branch2, went to main and merged it in, and again had a conflict where I selected the incoming branch2 change and now that reflects in helloworld.txt in main