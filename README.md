# Hidden_Markov_Model_for_POS_tagging
Uses Viterbi decoding algorithm for backtracking and assigning parts of speech to individual words.

To train the model, run hmmlearn3.py and then to use the model to classify, run hmmdecode3.py The code takes 1 input - The directory where training files are stored, and writes the model parameters to another text file which the code creates at runtime named hmmmodel.txt.

The hmmdecode3.py file creates another text file called hmmoutput.txt to write results in the format word/POS.
The code gives around 84% accuracy.
