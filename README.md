# Android-Twitter-Feed-App
This Android application fetches and displays Twitter feed for a user.

The main motivation behind by the application was to get a hands-on experience of Notifications, Asynchronous Tasks, Toast Messages
and Message Broadcasts.

The application starts by displaying the available Twitter feed to a user. After a certain period, it starts downloading the new
feed (if available) in a separate background thread. Since this downloading might take time,if the user switches to another
application during this period, the background thread places a download-complete notification in the Notifications bar. Otherwise,
it notifies the user via Toast message and makes the messages available for the user.

The main source code of this project spans the seven Java files uploaded in this repo. The remaining files are related to the
Manifest and layout.

A demo vidoe of the project in action can be found here: https://youtu.be/sBncxwNKDRM
