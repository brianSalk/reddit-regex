# Reddit Regex
This is a webapp that allows users to search for a word, phrase, or regex pattern in multiple subreddits.  
The hits are printed to the screen in the form of a link, making it super easy to find the submission.  
[Here](https://reddit-searcher.streamlit.app/) is the streamlit powered app.  
## Use Cases
This app has the following advantages over reddits built-in search function:
* You can use regex
* You can toggle case-senstivity
* You can show only whole-word matches
* You can limit the number of searches per query (i.e. only show 100 newest posts in animalrights matching `carni[sm][st]`)
* hits are displayed in a much more concise format, making it easier to find what you are looking for.
### Contribution
I greatly appreciate **any and all** contributions.  Submit a pull request or leave a note in the issues!  Here is a list of issues that the app currently has:  
* There is no good way to stop a current query and start over again with different parameters
* the code is messy.  Any help cleaning it, especially the giant 'find_string_in_subreddit' function would be great

