# Named-Entity-Recognition

### Description:- Create a named entity recognition system that identifies and classifies entities in user inputs.

### Solution:- Use a pre-trained NER model or train one using labeled data for entities like names, dates, and locations.

- We load the spaCy pre-trained model for English (en_core_web_sm).
- We define a function ner that takes user input, processes it using spaCy, and extracts named entities 
  along with their labels, start positions, and end positions.
- We provide an example user input sentence and call the ner function to extract named entities.
- Finally, we print the identified entities and their labels.
