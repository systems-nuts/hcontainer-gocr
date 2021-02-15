# hcontainer-gocr
ocr program

## How to use? 

the src have the source code, simply do make will generate the correct binary. 
It's a server based program, add -server as flag, unlike orignal GOCR program. The clinet program is in tool, also with the example pictures.
For normal use, simply do ./popcorn-gocr -i $imput_file
For server test use, do ./popcorn-gocr -server     serer test use needs a clinet.

### Before running

Please check the code, the PIC_SIZE of both gocr.c and client.c must be equal and the size has to be the size of example.png in byte 

### Example:

```

on machine A:
./popcorn-gocr -server
on machine B:
./clinet $ip_of_machine_A

```
