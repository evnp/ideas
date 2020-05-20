Vim plugin: word redudancy highlighter
- highlights words based on number of occurences in a document, from yellow to orange to red
- yellow-red spectrum is calculated based on two factors:
  - number of times the word appears in document
	- number of times the word appears in a paragraph
	- number of times the word appears in a sentence
  - length of word
- e.g. "the" appears frequently but is a short word. highlight: yellow
- e.g. "elegant" appears twice but is a long word. highlight: red
- intention: make word choice repetition immediately visible, so redundant word choices can be edited

Codepen-like web app that runs custom (local) js/css code using webpack HMR
