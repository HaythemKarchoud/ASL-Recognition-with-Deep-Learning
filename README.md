<h1> - American Sign Language with deep learning. </h1>


<h2>Description</h2>
In this notebook, I will train a convolutional neural network to classify images of American Sign Language (ASL) letters. After loading, examining, and preprocessing the data, we will train the network and test its performance.This technology often relies on complex neural network architectures that can detect subtle patterns in streaming video. However, as a first step, towards understanding how to build a translation system, the size of the problem is reduced by translating individual letters, instead of sentences.

<br />

<h2>Language and Libraries Used</h2>

- <b>Python </b> 
- <b>Pandas - Numpy - Keras - TensorFlow - matplotlib</b>


<h2> Code walk-through:</h2>

<p align="center">
Visualising the training data:  <br/>
<img src="https://i.imgur.com/CCh9ZAe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Examining the data set:  <br/>
<img src="https://i.imgur.com/PbSJYlB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
One-hot encode the data: <br/>
<img src="https://i.imgur.com/ApQb2rP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Define the model:  <br/>
<img src="https://i.imgur.com/aFGXGse.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
output:  <br/>
<img src="https://i.imgur.com/xyHWKCH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Compiling the model:  <br/>
<img src="https://i.imgur.com/TNacqYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Training the model:  <br/>
<img src="https://i.imgur.com/v4weBQd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Testing the model:   <br/>
<img src="https://i.imgur.com/q5GXGpg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Visualising mistakes:   <br/>
<img src="https://i.imgur.com/s4qh19q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
