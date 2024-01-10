# Some Fun AI-Projects    
## 1. Emojify
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/emojify.png" height = "300" width="600">

This is a model that uses word vector representations with an LSTM to build an Emojifier!

Have you ever wanted to make your text messages more expressive? Emojify will help you do that. So rather than writing "Congratulations on the promotion! Lets get coffee and talk. Love you!" the emojifier can automatically turn this into "Congratulations on the promotion! 👍 Lets get coffee and talk. ☕️ Love you! ❤️"

## 2. Face Recognition and Detection
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/faceDetect.png" height = "300" width="600">
Transfer learning with a pretrained model to map faces into 128 dimensional encodings to perform face recognition and detection.

Much of the ideas in this notebook came primarily from the following resources.
### References:
- Florian Schroff, Dmitry Kalenichenko, James Philbin (2015). [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/pdf/1503.03832.pdf)
- Yaniv Taigman, Ming Yang, Marc'Aurelio Ranzato, Lior Wolf (2014). [DeepFace: Closing the gap to human-level performance in face verification](https://research.fb.com/wp-content/uploads/2016/11/deepface-closing-the-gap-to-human-level-performance-in-face-verification.pdf) 
- The pretrained model we use is inspired by Victor Sy Wang's implementation and was loaded using his code: https://github.com/iwantooxxoox/Keras-OpenFace.
- Our implementation also took a lot of inspiration from the official FaceNet github repository: https://github.com/davidsandberg/facenet 



## 3. Music Generation 
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/music_sampling.jpg" height = "250" width="900">
The ideas in this notebook came primarily from three computational music papers cited below. The implementation here also took significant inspiration and used many components from Ji-Sung Kim's github repository.

- Ji-Sung Kim, 2016, [deepjazz](https://github.com/jisungk/deepjazz)
- Jon Gillick, Kevin Tang and Robert Keller, 2009. [Learning Jazz Grammars](http://ai.stanford.edu/~kdtang/papers/smc09-jazzgrammar.pdf)
- Robert Keller and David Morrison, 2007, [A Grammatical Approach to Automatic Improvisation](http://smc07.uoa.gr/SMC07%20Proceedings/SMC07%20Paper%2055.pdf)
- François Pachet, 1999, [Surprising Harmonies](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.5.7473&rep=rep1&type=pdf)

## 4. NMT with attention
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/nmt with attention.png" height = "400" width="500">
Neural Machine Translation (NMT) model to translate human readable dates ("25th of June, 2009") into machine readable dates ("2009-06-25").

## 5. Neural Style Tranfer
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/nst.png" height = "350" width="700">
 Optimize a cost function to get pixel values!
 
### References:
The Neural Style Transfer algorithm was due to Gatys et al. (2015). Harish Narayanan and Github user "log0" also have highly readable write-ups from which we drew inspiration. The pre-trained network used in this implementation is a VGG network, which is due to Simonyan and Zisserman (2015). Pre-trained weights were from the work of the MathConvNet team. 

- Leon A. Gatys, Alexander S. Ecker, Matthias Bethge, (2015). A Neural Algorithm of Artistic Style (https://arxiv.org/abs/1508.06576) 
- Harish Narayanan, Convolutional neural networks for artistic style transfer. https://harishnarayanan.org/writing/artistic-style-transfer/
- Log0, TensorFlow Implementation of "A Neural Algorithm of Artistic Style". http://www.chioka.in/tensorflow-implementation-neural-algorithm-of-artistic-style
- Karen Simonyan and Andrew Zisserman (2015). Very deep convolutional networks for large-scale image recognition (https://arxiv.org/pdf/1409.1556.pdf)
- MatConvNet. http://www.vlfeat.org/matconvnet/pretrained/


## 6. Signs Recognition
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/signs_data_kiank1.png" height = "200" width="500">
Classification of the Signs dataset 

## 7. Text Generation
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/textGen.png" height = "350" width="500">
Generate shakespare's style of poems.

### Refrences:
- This exercise took inspiration from Andrej Karpathy's implementation: https://gist.github.com/karpathy/d4dee566867f8291f086. To learn more about text generation, also check out Karpathy's [blog post](http://karpathy.github.io/2015/05/21/rnn-effectiveness/).
- For the Shakespearian poem generator, the implementation was based on the implementation of an LSTM text generator by the Keras team: https://github.com/keras-team/keras/blob/master/examples/lstm_text_generation.py 

## 8. Trigger word Detection
<img src="https://github.com/aobaruwa/TensorFlow-Projects/blob/master/Pix/TriggerWG.png" height = "300" width="600">
Speech Recognition applied to trigger word detection ("Activate"). Similar to Google Speech Assistant, Alexa and Siri.

- Structuring a speech recognition project
- Synthesizing and processing audio recordings to create train/dev datasets
- Training a trigger word detection model and make predictions


All the images used for illustration are Google Images.
