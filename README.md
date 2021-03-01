<div>
    <h1>RPS_Game :</h1>
    <p>A rock paper scissor game on web</p>
</div>

<div>
    <h1> UI </h1>
    <h3> In PC </h3>
    <img src="Result/res_1.png">
    <p>The Very First Page / Landing Page for the Game </p>
    <br>
    <img src="Result/res_3.png">
    <p>The Result Page</p>
    <br>
    <img src="Result/res_2.png">
    <p>Console Log for getting the information regardinhg the prediction from Computer </p>       
</div>

<div>
    <h1>Requirements :</h1>
    1 . ML Model
    <ul>
      <li>1 . To develope a Machine Learning algorithm to classify and detect the rock paper and scissor hand gestures</li>
      <li>2 . Model conversion so that we can use it for tensorflow js </li>
    </ul>
    2 . Web App
    <ul>
      <li>1 . Front -End :  UI for the Web Game ( It should contain a DIV which can render live damera feed so that a frame can be craptured for playing the game) </li>
      <li>2 . Back-End : for Routes and integrating the Tensorflow JS </li>
    </ul>
    3 . Deployment
    <ul>
      <li>1 . localhost:8000 </li>
      <li>2 . Virtual Machine ( weither in GCloud or Azure )</li>
      <li>3 . Docker Image</li>
    </ul>
</div>

<div>
    <h1>Privacy Concern</h1>
    <p>As the user is required to upload the image . We respect the Privacy of the user . We will use the Images for training our ML Model</p>
    <p>I am in the process of introducing the feature to delete your Data once you close the game</p>
</div>

# Tech Used
1 . Tensorflow , Tensorflow JS , Keras <br>
2 . JavaScript , Python<br>
3 . HTML , CSS<br>
4 . NodeJs , Express , Express-fileupload <br>

# How to use ?
<ul>
    <li>Using LocalHost <br>
        1 . clone this project <br>
        2 . npm install<br>
        3 . npm start<br>
        4 . Just upload a photo by using the upload button and that's it !! You are good to go.<br>
    </li>
    <li>Using Virtual Machine <br>
        1 . Create a VM on Google cloud / Azure  (os = linux) <br> 
        2 . Open the SSH terminal <br>
        3 . Install Nodejs <br>
        4 . clone this project  and * cd RPC_Game * <br>
        5 . npm start<br>    
    </li>
</ul>
Note you have to change the src for the image accordingly <br>
<div>
    <h3>Special Thanks</h3>
<p><a href="https://github.com/mohakbahal">Mohak Bahal</a> : For solving issue with Keras Model Conversion </p> 
</div>
