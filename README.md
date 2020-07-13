# Sentiment Analysis with node-red
Here you can see howto creat the sentment and emotion analysis with help of IBM node red.
# Getting the services:
- Go to IBM cloud page 'cloud.ibm.com' . If you dont have an account create new one or open your exsisting acount.
- Go to catalog-->search for NLU--> leave all as it is --> and click create.22
- Go to catalog-->search for Tone analyser--> leave all as it is --> and click create.22
- create youe twitter developer account as per the instruction given in the twitter  node.

# Creat node-red flow:
- Open your Node-red. settings-->import and just import the 'version5.1.json' file.
- There you can see the 2 node namely natural language understanding and Ton analyser. Tone analyser is for analysing the emotions of people and NLU is for analyze the sentiments.
22
- open the NLU node and copy paste the API key,URL from your service credential page.22
- open the Tone analyser node and copy paste the API key,URL from your service credential page.22
- Inside the twitter node copy paste the twitter API crendentials.22
- Change your file node location to your local location.22
- Click on deploy.
###### you can see the result nd tweets are streaming now.22
