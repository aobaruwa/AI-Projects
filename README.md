# TensorFlow-Projects  
![](../master/Pix/tf.png)
## Emojify
![](../master/Pix/emojify.png)
This is a model that uses word vector representations to build an Emojifier!

Have you ever wanted to make your text messages more expressive? Emojify will help you do that. So rather than writing "Congratulations on the promotion! Lets get coffee and talk. Love you!" the emojifier can automatically turn this into "Congratulations on the promotion! 👍 Lets get coffee and talk. ☕️ Love you! ❤️"

It inputs a sentence (such as "Let's go see the baseball game tonight!") and with an LSTM and word vectors it finds the most appropriate emoji to be used with this sentence (⚾️). It also shows that with a good language model, it can generalize and associate words in the test set to the same emoji even if those words don't even appear in the training set.  This makes it an accurate classifier mapping from sentences to emojis, even using a small training set. 

