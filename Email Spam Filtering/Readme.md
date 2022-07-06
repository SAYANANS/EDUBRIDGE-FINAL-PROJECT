# <div align="center"><u><b>Spam Mail Classification</b><u></div>
  <h5>AIM:</h5>
 - Build a model to predict the mail is spam or not
  <h5>Overview:</h5>
  <p>what is spam mail?<br>
    Email spam, also known as junk email, refers to unsolicited email messages, usually sent in bulk to a large list of recipients. Spam can be sent by real humans, but more often, it is sent by a botnet, which is a network of computers (bots or spambots) infected with malware and controlled by a single attacking party (bot herder). Apart from email, spam can also be distributed via text messages or social media.</p>
  <h5>Dataset Details:</h5>
  <table>
  <tr>
    <th>Field</th>
    <th>Description</th>
  
  </tr>
  <tr>
    <td><u>Category<u></td>
    <td>spam or ham</td>
  </tr>
     <tr>
    <td><u>Message<u></td>
    <td>The received mail<u></td>
  </tr>
  </table>
      
<h5>Implementation:</h5>

<u>**Libraries:**<u> 
    `NumPy`  `pandas` `sklearn`  `Matplotlib`  `Seaborn`
  <h5>Approach:</h5>       
  Here, the models used are 

* Logistic Regression
* Naive Bayes
* Random Forest
<h5>Comparing all Models:<h5>

<table>
 <tr>
   <th>Model</th>
   <th>Accuracy</th>
   </tr>
 <tr>
   <td><u>Logistic Regression<u></td>
   <td>0.979372197309417</td>
  </tr>
 </tr>
  <tr>
    <td><u>Naive Bayes<u></td>
    <td>0.9883408071748879</td>
    </tr>
        </tr>
  <tr>
    <td><u>Random Forest Classifier<u></td>
    <td>0.9766816143497757</td>
    </tr>
  </table>
      
  <h5>Naive Bayes is the best from among the models trained to predict the accurate result with an accuracy of 0.9883408071748879.<h5>
        
  
