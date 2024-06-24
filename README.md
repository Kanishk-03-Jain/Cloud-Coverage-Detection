# Cloud-Coverage-Detection
The purpose of this project is to build predictive models for cloud coverage prediction after the next 15, 25 and 30 minutes, given the data of past 360 minutes (6 hours) .

Documentation: https://docs.google.com/document/d/1NSPt0MgcluKspor2198lxPtN2d6iwSOQ0dYxeXy9AS4/edit?usp=sharing
<br>

## Models Implemented
1) Simple RNN (Recurrent Neural Network)
2)  GRU (Gated Recurrent Unit)
3) LSTM (Long Short Term Memory)
4) Custom LSTM (LSTM with concat layers)
5) AutoEncoders
6) Transformers
7) Conv1D + LSTM layers

## Set-Up
Paste these commands in the command prompt of your working directory to get started.
~~~
git clone https://github.com/Kanishk-03-Jain/Cloud-Coverage-Detection.git
cd Cloud-Coverage-Detection
python3 -m pip install -r requirements.txt
~~~
Get weights from the drive link https://drive.google.com/drive/folders/1AHORQ4eyikaWXs-oBANKckeCJJS0M735?usp=sharing and save them in the ```weights``` folder which is present in the cloned file directory.

Also get the ```train.csv``` and ```CCD test.csv``` file from the above drive link
