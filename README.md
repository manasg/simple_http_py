One of the most common examples - Python Simple HTTP Server, with interface as an option. Courtesy stack overflow

```
python server.py 127.1.1.1:8080
```

```
manas@lem1:~/repos/simple_http_py$ ss -lnt
State       Recv-Q Send-Q Local Address:Port               Peer Address:Port              
LISTEN      0      10     127.0.0.1:2222                       *:*                  
LISTEN      0      5      127.1.1.1:8080                       *:*                  
LISTEN      0      5      127.0.1.1:53                         *:*                  
LISTEN      0      10     127.0.0.1:2200                       *:*                  
LISTEN      0      5      127.1.0.1:8000                       *:*
```
