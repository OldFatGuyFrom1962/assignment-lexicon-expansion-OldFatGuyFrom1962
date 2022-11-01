# assignment-lexicon-expansion-OldFatGuyFrom1962
# Lexicon Expansion

This assignment continues the work from the "Lexicon Expansion" work discussed in lecture/class. The idea is
relatively simple: take a word or set of words that you think are emblematic of a subset of your corpus, and expand that
to create a larger vocabulary that you can use in other contexts. 

In this assignment you have a few options for the work you'll do. You can work with the convention data corpus, the Twitter descriptions
you pulled as part of that assignment, or the vaping Twitter data I shared. Regardless of how much you know about these topics, I'd 
like you to treat this corpus as one you're relatively ignorant of. For instance, if you follow politics closely and know tons of 
buzzwords Republicans or Democrats are likely to use, just start with a word or two so you can see how well your algorithm works. 

Here are the steps I'd like you to follow: 

1. Inspect the corpus manually, perhaps by looking at a random selection of 50 or 100 tweets/descriptions/speech parts. 
2. Find between one and three words that you think are "interesting" in the sense that they might be emblematic of a certain subset of people in the corpus. This could be a word that appears in the Twitter description, a word from a speech, or a word like "school" in the vaping corpus. 
3. Divide the data set into two groups: text that includes that word and text that does not. 
4. Use the techniques from class or lecture to find words that are unusually highly represented in the group that includes the word. 
5. Look at that list of words and expand your word set to include some new words. 
6. Repeat 3-5 a few times. Stop at a place that seems sensible. 
7. Once you've finalized your word list, divide the corpus into two groups: the half that has those words and the half that doesn't. Then do some comparison between the two groups, either using the Group Comparison assignment or other mechanism. 


Again, no starter code for you here. I'd like you to produce a notebook that, when the cells have run, produces something that looks closer to a "written report" than what we've been doing, which I would describe more as code. Take advantage of the markdown cells to write prose about what you've done and what conclusions you've drawn. It's fine to have code and code output, but think of this like a blog post for a technical audience. 
