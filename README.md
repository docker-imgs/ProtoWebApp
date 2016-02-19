ProtoWebApp
===========

docker  run  node.js


### install

docker run  -itd -p 3000:3000 --name ProtoWebApp -v "$(pwd)":/webapp -w /webapp  alpine-node npm start