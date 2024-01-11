
## Start the bert service in the console
Download the model from here https://tfhub.dev/google/bert_uncased_L-12_H-768_A-12/1
And place the folder in the project directory

Go to bert-server.py and replace the model_dir value to your downloaded folder's path
```
python bert-server.py
```

## Testing the bot
Open another anaconda prompt 
```
conda activate chatbot


python chatbot.py
```
It will ask you query. Ask your question and it will be answered.!


## Ask the bot Questions like

* Who sits on a local complaints committee?

* Can the landlord increase my rent?
