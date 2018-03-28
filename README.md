# Twitter Community Detection

This code gets all the friends and followers of 'TheRealStanLee' and builds a friendship graph

It Crawls their followers, with depth 3 and limit 5 for each level

Gets the friends and followers of them and store it in a dict format

It then, extracts reciprocal friends through these two lists, with a distance of 1

From this new list, it selects top 5 followers and get the friends and followers of depth 2 and a limit of 5 for each level

and saves it to a .json file

Then, using this data it creates a community graph and colors the nodes wrt to the different communities they belong to

-----------------------------------------------------------------------------------------------------

P.S.: you have to create your twitter developer account in order to get the following information:
- consumer_key
- consumer_secret
- token
- token_secret

and you can then store this info in a file (I have stored it in the auth_dict file)
whose location will be the current folder of the .ipynb file
it will be of json format

-----------------------------------------------------------------------------------------------------
