# Arabic-Semantic-Error-Detection-and-Correction
Arabic Semantic Error Detection and Correction using Language Model

# preprocessig 
After we read our dataset from the files we removed punctuations and numbers from our text. and count the max text count for our sentence and our groundtruth.and used Tokinzer to convert our text to tokens to fit to our model.


# Model
our approah is Language Model so we wanted to use Seq2Seq model . so we used LSTM Model which has 3 Encoder and one decoder with one Embeding Layer to each one and used adam optimizer for our optimizer and sparse_categorical_crossentropy to calcaulate our Loss.our batch size is 32 and trained 30 Epochs. 


# Evaluation
our model gaves us 77.97 train accuracy and 52,57 valditaion accuracy.we used Word Error Rate to evaluate our model which gives us 1.065687944852582
