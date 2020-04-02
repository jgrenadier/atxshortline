# atxshortline
A webpage and SignalR server for realtime information on Austin grocery store status

I thought it might be useful 
if there was an method where people could check in realtime 
if their local Austin grocery store was very busy. Stores like HEB do a great
job of helping customers maintain social distancing by limiting the
number of customers in the store at any one time.  But it would
be better if people could avoid having to standing together in long lines
outside the store.

So, I built a simple web page and SignalR based server in the cloud.
It's basically a chat program.  The options are intentionally very limited.
I think you want to focus on the simple binary question of "is the store
busy" and discourage postings like "They have wipes, so lets mob the store".

I was able to go from idea to working prototype deployed in the cloud.
As in most software, the first 90% is easy. The rest takes alot more time.
In this case, the first implementation...

     * Only shows people's new posts you start the app. No historical database.
     
     * Is a webpage not an app. However it does work reasonably well
       on my android phone chrome browser both in portrait and landscape mode.
       
     * The fonts are a bit small.
     
     * only lets you select a two austin store names for now but the
       user can type in any name they like.

Anyway, it let me keep a bit of sanity while coding.
Let me know if anyone has ideas on whether this is a good idea and what
direction to go with it.  

Here's a link:  https://www.atxshortline.info

Eventually, I'll put the code for this project up here on Github.
For now, this is placeholder describes the project.

