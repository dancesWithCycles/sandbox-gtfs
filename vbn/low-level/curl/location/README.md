$ curl -v -o output-file http://www.connect-info.net/opendata/gtfs_output/\/token\/_connect-with_low_level_stops.zip
* Expire in 0 ms for 6 (transfer 0x560fbb092c70)
* Expire in 1 ms for 1 (transfer 0x560fbb092c70)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* Expire in 0 ms for 1 (transfer 0x560fbb092c70)
* Expire in 1 ms for 1 (transfer 0x560fbb092c70)
...
* Expire in 2 ms for 1 (transfer 0x560fbb092c70)
*   Trying 62.154.206.91...
* TCP_NODELAY set
* Expire in 200 ms for 4 (transfer 0x560fbb092c70)
* Connected to www.connect-info.net (62.154.206.91) port 80 (#0)
> GET /opendata/gtfs_output/\/token\/_connect-with_low_level_stops.zip HTTP/1.1
> Host: www.connect-info.net
> User-Agent: curl/7.64.0
> Accept: */*
> 
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0< HTTP/1.1 200 OK
< Server: Apache-Coyote/1.1
...
< Accept-Ranges: bytes
< ETag: W/"62680558-1632564256000"
< Last-Modified: Sat, 25 Sep 2021 10:04:16 GMT
< Content-Type: application/zip
< Content-Length: 62680558
< Date: Sat, 25 Sep 2021 10:06:01 GMT
...
< Cache-control: private
< 
{ [1026 bytes data]
100 59.7M  100 59.7M    0     0  5824k      0  0:00:10  0:00:10 --:--:-- 6995k
* Connection #0 to host www.connect-info.net left intact
