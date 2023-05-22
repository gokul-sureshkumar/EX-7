# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

DATE :

AIM :
```
To write the python program for simulating Traceroute command

```
ALGORITHM :
```
Start the program.
Get the frame size from the user.
To create the frame based on the user request.
To send frames to server from the client side.
If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
Stop the program
```

PROGRAM :
```python
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```

OUTPUT :

![image](https://github.com/gokul-sureshkumar/EX-7/assets/121148715/e102b4fb-dc48-4406-a6ad-d4fb598568f4)


RESULT :

Thus, the python program for simulating Traceroute command was successfully executed.

