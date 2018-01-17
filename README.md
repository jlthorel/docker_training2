# docker_training
Link

https://mensuel.framapad.org/p/docker0118


Lien presentation :
    https://docs.google.com/presentation/d/1u1AtyoRZZdREEBOLTslfYxykJ5Z5n9DyKjoOrHmMbL4/edit?usp=sharing
    
    
    https://blog.jessfraz.com/post/windows-for-linux-nerds/
    
    https://docs.docker.com/engine/installation/

   https://github.com/moby/moby/blob/master/oci/defaults.go#L14-L30

https://github.com/moby/moby/blob/master/profiles/seccomp/default.json

https://docs.docker.com/engine/reference/commandline/ps/#formatting


vim /etc/resolv.conf

https://github.com/revollat

http://supervisord.org/

https://docs.docker.com/compose/extends/
https://github.com/revollat/micro-php-app-docker
https://blog.jessfraz.com/post/docker-containers-on-the-desktop/


git remote add origin https://github.com/jlthorel/docker_training.git
    


    
git add  .
git commit -m "first commit"
git push -u origin master


Day 1
TP 1
docker image build -t jthorel/lauers1 -f Dockerfile.base .
docker image history jthorel/layers1

docker container run -it jthorel/layers2
ctrl p ctrl q  pour sortir du shell sans terminer le container

docker container ps

docker container diff 353070dc627d

htop
