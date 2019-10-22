# UniqueNewsFeed
The idea here is to create an unbiased, sentiment balanced, non-repetitive and relevant news-feed that can provide news for any specified location by utilising the Twitter API. Twitter feed is chosen here because it is not organisation driven and has near instant updates. The program does the following:
First, it authenticates the twitter access credentials and gets the twitter 'app' running. 
Next, it jots down the date and time of the app being accessed, while simultaneously checking log of previous entry. 
If the dates don't match, it wipes the taglist(which is instrumental in keeping track of topics completed, will be explained later in this 'readme') and  updates last entry log. 
It then asks user for the type of news expected, i.e, World, Country, State, District. It then proceeds to list out the news from that location by finding trending hashtags and using twitter api to search for it. It then provides topics which are unique with three options, to either have a sentiment balanced view(To avoid overwhelming negative or positive news), to view all top tweets or to skip the topics.
As the topics for the day are added, the user find the number of topics yet to be read, decreasing. 
Also, if the topic is not in the language of the user's preference, the translated version is presented along with the original text with a note below that mentions that it has been translated. It also makes sure to censor any vulgar language. 
Then, the user is periodically given the option to quit the program.
