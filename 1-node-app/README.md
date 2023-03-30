    1  apt-get update
    2  apt-get install curl -y
    3  curl -sL https://deb.nodesource.com/setup_10.x | bash
    4  apt-get install nodejs -y
    5  ls
    6  cd opt/
    7  mkdir node-app
    8  echo 'console.log("nodejsapp from ubuntu 18.04 ...");' > index.js
    9  cat index.js
   10  node index.js
   11  history
