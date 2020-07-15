# Text_Predictor
<h2>The Dataset</h2>
In order to train this sequence model, the popular Drama/Indie screenplay Good Will Hunting was used.
This corpus comprised of a total of **3293** unique words.
Data preprocessing steps included removing whitespaces from the text file, converting the texts to lowercase and tokenizing them.
<h2>Architecture</h2>
The model uses 3 layers in total:
  1) An Embedding Layer 
  2) A Bidirectional LSTM layer with 150 units
  3) A Dense Layer with SOFTMAX Activation
<h2>Performance</h2>
The model was trained using the Adam optimizer with Categorical Cross-Entropy as the loss function.
Over 30-35 epochs, the training converged with an accuracy close to 90% with an average loss close to 0.5.


