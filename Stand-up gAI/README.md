Trying to get an AI to generate the script of a stand-up comedy show, using data gathered from multiple Netflix specials and other transcripts.
All data was put into a single txt file with no indication of the comedian's names (maybe using a variety of styles was a bad idea). 

The model itself is an RNN that remembers context and tries to replicate the script in the same fashion by predicting one word at a time, starting from a given 'prime' word. 
