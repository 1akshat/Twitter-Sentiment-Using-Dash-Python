# Twitter-Sentiment-Using-Dash-Python
<p>Live Twitter Analytics using Dash Python</p>
<p>Go to https://apps.twitter.com/ and create new app.</p>
<p>Catch your required creadentials and put in lines 27,28,29,30 in twitter_sentiment_stream.py file.</p>
<p>Create a virtual env using command<pre>virtualenv env</pre> and activate the environment using <pre>source $envname/bin/activate</pre></p>
<p>Now install all the dependencies using <pre>pip install -r requirements.txt</pre></p>
<p>Run the script using python twitter_sentiment_stream.py using <pre>python twitter_sentiment_stream.py</pre></p>
<p>This will create a twitter.db sqlite3 database. Keep this script running and in the new terminal window run other script using python dash_sentiment_analysis.py.</p>
<p>Now open the route on localhost. You will see streaming data on the webpage.</p>
<p>You can change the keyword on the searchbar. It's default value is twitter.</p>