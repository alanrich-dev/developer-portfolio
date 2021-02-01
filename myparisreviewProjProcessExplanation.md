To solve the problem I decided on a NoSQL database of three collections. A collection of stories stories. A global collection of stories. A global collection of summaries divided into sub-collections for each story. Entries in each collection received a unique identifier as well as an identifer shared with entries of the same title existing in the other collection. Having this unique & shared ID scheme seemed like an easy solution to my query needs. 

I wanted users to be able to search an offline collection of theparisreview.org archives and have some options with each search result: navigate to that story's url, read story summaries submitted from other subscribers, add to the user's collection of reading reaad or recommended.

***Users should have a profile page prominently displaying their recommended stories and minorly displaying their currently reading, library and a fading carousel of clickable summariesz
