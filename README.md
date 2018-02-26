# tensorflow-speechtotext-windows-instalation

Run train.py 
https://www.tensorflow.org/versions/master/tutorials/audio_recognition

open the documentation 
https://www.tensorflow.org/versions/master/get_started/premade_estimators

before install pandas
you must set environment variable in windows
Click Start > Right Click Computer > Properties > Advance System Setting > Environment Variables > Path > Edit > add ; in last Path >> 

add the location where you installed python and folder scripts , example C:\Users\YourName\AppData\Local\Programs\Python\Python36;C:\Users\KharisAzhar\AppData\Local\Programs\Python\Python36\Scripts

Next 

Open CMD (windows+R)
input this command

  * pip install pandas
  
Wait until finish

then clone the github repository git clone https://github.com/tensorflow/models and 
https://github.com/tensorflow/

Change directory within that branch to the location containing the examples used in this document:
  cd tensorflow/examples/speech_commands

Start train.py , open cmd then 
    * python train.py
  
   




