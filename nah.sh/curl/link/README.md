$ curl -v -o output-file http://www.connect-info.net/opendata/gtfs/nah.sh/\/token\/
* Expire in 0 ms for 6 (transfer 0x563ed9a74c70)
* Expire in 1 ms for 1 (transfer 0x563ed9a74c70)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* Expire in 3 ms for 1 (transfer 0x563ed9a74c70)
* Expire in 2 ms for 1 (transfer 0x563ed9a74c70)
...
* Expire in 4 ms for 1 (transfer 0x563ed9a74c70)
*   Trying 62.154.206.91...
* TCP_NODELAY set
* Expire in 200 ms for 4 (transfer 0x563ed9a74c70)
* Connected to www.connect-info.net (62.154.206.91) port 80 (#0)
> GET /opendata/gtfs/nah.sh/\/token\/ HTTP/1.1
> Host: www.connect-info.net
> User-Agent: curl/7.64.0
> Accept: */*
> 
< HTTP/1.1 302 Found
< Server: Apache-Coyote/1.1
...
< Location: http://www.connect-info.net/opendata/gtfs_output/\/token\/_Opendata-SH.zip
< Content-Length: 0
< Date: Sat, 25 Sep 2021 10:17:07 GMT
...
< 
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
* Connection #0 to host www.connect-info.net left intact
