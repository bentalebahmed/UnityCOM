# UnityCOM
Package for using serial communication in Unity3d in Windows

## How it Works

Pair your port with you computer.

Add SerialCOM to a GameObjct. 

Use SerialWrapper script to read or write data.


## Installation

In Player Settings -> other Settings use .NET 4.x

Add unityPackage to Unity, in folder serial communication you will find a scene "New Scene" to test the COM port (teseted on Arduino uno, nano).

For the incoming data, SerialCOM script reads till new line appears ('\n').

## License
[MIT](https://choosealicense.com/licenses/mit/)
