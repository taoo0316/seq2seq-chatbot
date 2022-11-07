# Seq2Seq Chatbot

This is a 200 lines implementation of Twitter/Cornell-Movie Chatbot, please read the following references before you read the code:

- [Practical-Seq2Seq](http://suriyadeepan.github.io/2016-12-31-practical-seq2seq/)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) (optional)

### Prerequisites

- Python 3.6
- [TensorFlow](https://github.com/tensorflow/tensorflow) >= 2.0
- [TensorLayer](https://github.com/zsdonghao/tensorlayer) >= 2.0

### Model

<table class="image">
<div align="center">
    <img src="http://suriyadeepan.github.io/img/seq2seq/seq2seq2.png"/>  
    <br>  
    <em align="center"></em>  
</div>
</table>

### Training

```
python3 main.py
```


### Results

```
Query > happy birthday have a nice day
 > thank you so much
 > thank babe
 > thank bro
 > thanks so much
 > thank babe i appreciate it
Query > donald trump won last nights presidential debate according to snap online polls
 > i dont know what the fuck is that
 > i think he was a racist
 > he is not a racist
 > he is a liar
 > trump needs to be president
 ```
 
 ### Results for Marx-related Seeds (1 epoch)
 
 ```
 Query > What is the philosophy of Marx?
 > i am so excited
 > i dont want to be so excited for you 
 > i dont know it is so bad and i am in this   
Query > How is your buddy Engels, Marx?
 > i think i am going for that one   
 > i am so good for that 
 > i think i am going to get a new one
 Query > What is the philosophy of Marx?
 > i know that was the best thing i have to go
 > i think it is so cute 
 > i am going to get it to the debate  
Query > How is your buddy Engels, Marx?
 > i think i was so excited for that 
 > i think that was a great time
 > i think i have no one
```

### Results Trained on Marx-related Movies (50 epochs)

```
Query > What is your view of communism?
 > and enough framed white back hand      young
 > and enough set blood time 
 > and fuck blood back out  
Query > What is your view of capitalism?
 > and happy sits happy squeezes ass 
 > and happy sits happy and on still wet fire  
 > and fuck blood enough again time holding time   
Query > What is the philosophy of Marx?
 > you theyre ending blood life  it   
 > you claim long life spiral shape starts talk this ends 
 > you theyre gets clothes scrimmaging park   still walks up reads  heard 
Query > How is your buddy Engels, Marx?
 > boss squeezes sits beat hand sunglasses  
 > boss gets sits bed checks hand turns it m street hand  took go get street   woman sign
 > boss enters tries bed checks coming time  took it reads 
```
