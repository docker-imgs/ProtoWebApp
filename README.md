ProtoWebApp
===========

docker  run  node.js

docker run --rm -itd -p 3000:3000 --name ProtoWebApp -v "$(pwd)":/webapp -w /webapp  node npm start