$ curl -v -o output-file http://www.connect-info.net/opendata/gtfs_output/\/token\/_Opendata-SH.zip
* Expire in 0 ms for 6 (transfer 0x55b31fe27c70)
* Expire in 1 ms for 1 (transfer 0x55b31fe27c70)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* Expire in 0 ms for 1 (transfer 0x55b31fe27c70)
* Expire in 2 ms for 1 (transfer 0x55b31fe27c70)
...
* Expire in 2 ms for 1 (transfer 0x55b31fe27c70)
*   Trying 62.154.206.91...
* TCP_NODELAY set
* Expire in 200 ms for 4 (transfer 0x55b31fe27c70)
* Connected to www.connect-info.net (62.154.206.91) port 80 (#0)
> GET /opendata/gtfs_output/\/token\/_Opendata-SH.zip HTTP/1.1
> Host: www.connect-info.net
> User-Agent: curl/7.64.0
> Accept: */*
> 
< HTTP/1.1 200 OK
< Server: Apache-Coyote/1.1
...
< Accept-Ranges: bytes
...
< Last-Modified: Sat, 25 Sep 2021 10:17:07 GMT
< Content-Type: application/zip
< Content-Length: 21017424
< Date: Sat, 25 Sep 2021 10:18:01 GMT
...
< Cache-control: private
< 
{ [14058 bytes data]
100 20.0M  100 20.0M    0     0  5120k      0  0:00:04  0:00:04 --:--:-- 5120k
* Connection #0 to host www.connect-info.net left intact
