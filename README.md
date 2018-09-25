# french-genanki-jupyter
A jupyter notebook creating anki cards.  The script loads csv to search then gets data from bing images api, and collins dictionary.  The script tries to get culture / language specific images.

It creates cards for testing:
* comprehension based on the image (without words)
* generation (thinking of the word with a picture cue)
* pronunciation (with audio and IPA)
* spelling
* quizzing the gender of nouns


## Requirements
* You need to get a bing image api key, (which costs about $US 5 per 1000 queries)
* you must install the following python libraries:
  * jupyterlab
  * python-resize-image
  * requests
  * BeautifulSoup
  * yaml
