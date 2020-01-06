# wordsToDefinitions
Look up words and quickly export them alongside their definitions to a csv file for easy importing into anki. 


## My Typical Usuage
I am trying to improve my vocabulary by reading. I come accross lots of new words that I want to remember. Anki is the best way for me to ensure that I will accomplish this. So, I built this tool to make it super easy to add definitions of new words that I come accross while reading. At the end of a session, all the definitions are in 'definitions.csv' and you can import that into anki. 

## Structure of cards
As of now I only have 3 fields (columns) for each word.
1. word
2. ipa (pronunciation of word using ipa notation)
3. definition 

at this point 3 might not always be pretty. Keep in mind I just took xml from definitions in Oxfd lrnrs dtic, did a little clean up, then plopped it in there.

## To do
1. add prefix tree to allow for autocompletion
2. take advantage of the structure of stardict files rather than building the words into a python dict
3. extract audio files from dict files and add as another field to export
4. make command line options possible rather than only interactive mode
4.1 read list of words
4.2 change output dir
4.3 read arbitrary number of words separated by spaces
5. gui
