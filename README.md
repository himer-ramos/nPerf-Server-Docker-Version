# nPerf-Server-Docker-Version
A docker version for nPerf servers network


# spanish
Si necesita unirse a la red de nPerf speedtest, (https://www.nperf.com/es/)
esta imagen le sera util

una vez terminada puede probar los tests en  : 
https://server-check.nperf.com/

# english
if your need join to nperf speedtest
this image will be useful

when done you can try the test on : 
https://server-check.nperf.com/


#build 
docker  build  -t  sirio_nperf_img  .

#run
docker run --name=sirionperf_run -d -p 160.20.225.11:8081:8080 -p 160.20.225.11:8443:8443 -p 160.20.225.11:80:8080 -p 160.20.225.11:443:8443  sirio_nperf_img

