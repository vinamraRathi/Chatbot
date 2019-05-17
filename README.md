# Chatbot

My goal was to create a chatbot that could talk to people in real-time, and not sound like a total idiot.

The dataset I accquired was from Reddit comments and it can be found here
https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment/?st=j9udbxta&sh=69e4fee7 

Each months Dataset is atleast 5-6 Gb in Size. I have used One month dataset which can be downloaded throug this link :
magnet:?xt=urn:btih:7690f71ea949b868080401c749e878f98de34d3d&dn=reddit%5Fdata&tr=http%3A%2F%2Ftracker.pushshift.io%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A80

In databse Folder I have cleaned my dataset from the Redit's comment and unneccessary traffic.
In Creating Dataset Folder I have created a reply to and from for every comment of each parent and it's child's reply.
Where to contains reply to parents and from contains reply from parent. 

I am planning to train my model by applying different algorithms and checking the accuracy. For now I am going to implement a LSTM model and aslo a CNN approach to see how it works. 
