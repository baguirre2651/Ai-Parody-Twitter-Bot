## Ai-Parody-Twitter-Bot
For this project I thought it would be fun to create a parody bot account mimicking and predicting funny and sarcastic tweets from myself.


![MAIN T](https://github.com/user-attachments/assets/a1867344-08ce-4e19-9b0a-200180df7fd4)  (main account)
# Creating The Bryan Aguirre Twitter Parody

![Parody](https://github.com/user-attachments/assets/49bf57bd-0c8c-4ec7-8454-fa9a32597577)



# Here's the Gist of how it will work:
 1. A user @mentions your bot @b_ryanaguirre_ or Bryan Aguirre (Parody)
 2.The script starts by finding a new @mention and then reads the parent tweet it is being mentioned on
 3.The script will then take that parent tweet and generates a witty response or own tweet using the language model (GPT 4)
 4.Respond is posted and tweet is logged


 # Fat Cat.JSON
 -Creating our LLM
 -we start with creating a function that will take in/feed in my tweet, and give an output response.

 -We are making sure it is under 200 characters and creating around a 5-10 min response window given the norm behind twitter limits.
 -Started first by using twitter developer mode to create Bryan Aguirre (Parody) in order to obtain API keys for this project.
 -Our Fat Cat JSON file is where we worked on our LLM and prompt tweaking for our liking. 

# Reply Bot.py
 Created a twitter bot class top help organize code and manage shared state
   -Used @Airtable to host database, since it is easy and all you need is a simple API 
   - checks how many tweets to repond to each time the program wakes up
   - using GPT 4 lanugae model with a tempature of .5 for creativity.
   - Go throughs our prompt and generate an output
   - Take a text(parent tweet (my tweet) and will generate a reponse that will then create a tweet


# Push To Github
Created a master job function using Python Schedule library to run the script to run in between every 5-10 minutes. 

Pushed to Github (Remote Code Hosting)

Used @Railway.app to host applictions from this repo.
Railway(an infrastructure platform where you can provision infrastructure, develop with that infrastructure locally, and then deploy to the cloud)
Creating our enviroment to run on scheduled time.


# Test on Twitter 




 
