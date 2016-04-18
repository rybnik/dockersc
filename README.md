# dockersc

A proof of concept Dockerfile birthcert. Uses [dockerfile-parse](https://www.npmjs.com/package/dockerfile-parse) and [validate-dockerfile](https://www.npmjs.com/package/validate-dockerfile). 

<pre>
$ node docker-birthcert.js Dockerfile
{"baseimage":"ubuntu:14.04","bom-depends":["smbclient"]}
$ node docker-birthcert.js Dockerfile3
{"baseimage":"ubuntu:14.04","bom-depends":["aufs-tools","automake","build-essential","curl","dpkg-sig","libcap-dev","libsqlite3-dev","mercurial","reprepro","ruby1.9.1","ruby1.9.1-dev","s3cmd"]}
</pre>
