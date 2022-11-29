# docker overview for the project based

## Docker overview :
=============================
# if you start docker server newly then execute this command :

  ``` 
  sudo chmod -R 777 /var/run/docker.sock
  
  ```

### docker used commands to 

```
ADD 
COPY 
CMD 
ENTRYPOINT 
STOPSIGNAL
HEALTHCHECK
```


ADD : similar to the COPY command ,but can also pull files using a URL and extract archive into 
      loose files in the image .
	  
	  
curl localhost:8081

kubectl version

kubectl get pods

kubectl get nodes

-f == helpfull to run the other director location .

.(dot) ---> means same directorie

cp ../ineligible/hello.go ./

```
how to see docker image metadata-- docker image inspect imagename(nginx)
```


untagged images is  danglling images ---->docker image prune 

docker container ls or docker ps

docker container rm -f nginx


flattening of docker images ---->  forming of single layer

> how many layers in docker image if wnat to find use this command

```
docker image history nofloat  
```     


docker export containername  > archive file(flat.tar)

docker export and import command helpfull to to reduce the layers of images .if you reduce the layers , performance will be increase.
but size will be same.


pubic registry -does not contain authatcation and tl certifacates 





