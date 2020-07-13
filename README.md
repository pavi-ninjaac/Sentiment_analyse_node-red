# Sentiment Analysis with node-red
Here you can see howto creat the sentment and emotion analysis with help of IBM node red.
# Getting the services:
- Go to IBM cloud page 'cloud.ibm.com' . If you dont have an account create new one or open your exsisting acount.
- Go to catalog-->search for NLU--> leave all as it is --> and click create.

![Screenshot (184)](https://user-images.githubusercontent.com/51699297/87297063-6fe59480-c525-11ea-8892-907d8a9acfbf.png)

![Screenshot (185)](https://user-images.githubusercontent.com/51699297/87297085-770ca280-c525-11ea-8cde-9402f55f9191.png)

- Go to catalog-->search for Tone analyser--> leave all as it is --> and click create.22
- create youe twitter developer account as per the instruction given in the twitter  node.

# Creat node-red flow:
- Open your Node-red. settings-->import and just import the 'version5.1.json' file.

![Screenshot (187)](https://user-images.githubusercontent.com/51699297/87298411-c81d9600-c527-11ea-82d0-6ae7d9768bb1.png)

- There you can see the 2 node namely natural language understanding and Ton analyser. Tone analyser is for analysing the emotions of people and NLU is for analyze the sentiments.

![Screenshot (186)](https://user-images.githubusercontent.com/51699297/87297089-796efc80-c525-11ea-9e8e-89647133c056.png)

- open the NLU node and copy paste the API key,URL from your service credential page.22
- open the Tone analyser node and copy paste the API key,URL from your service credential page.

![Screenshot (79)](https://user-images.githubusercontent.com/51699297/87298292-94427080-c527-11ea-913c-64fb356f1c0f.png)

![Screenshot (80)](https://user-images.githubusercontent.com/51699297/87298457-da97cf80-c527-11ea-8978-ef1f84889c49.png)

- Inside the twitter node copy paste the twitter API crendentials.

![Screenshot (113)](https://user-images.githubusercontent.com/51699297/87298390-be942e00-c527-11ea-97da-6178f64c53a4.png)

- Change your file node location to your local location.22
- Click on deploy.
#### you can see the result nd tweets are streaming now.

![Screenshot (186)](https://user-images.githubusercontent.com/51699297/87297089-796efc80-c525-11ea-9e8e-89647133c056.png)

