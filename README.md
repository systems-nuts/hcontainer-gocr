# hcontainer-gocr
ocr program

## How to use? 

the src have the source code, simply do make will generate the correct binary. 
It's a server based program, unlike orignal GOCR program. The clinet program is in tool, also with the example pictures.


### Before running

Please check the code, the PIC_SIZE of both gocr.c and client.c must be equal and the size has to be the size of example.png in byte 

### Example:

```

on machine A:
./popcorn-gocr -server
on machine B:
./clinet $ip_of_machine_A

```
