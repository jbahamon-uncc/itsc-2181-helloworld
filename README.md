git config --global http.sslVerify false
git config --global user.name "your name"
git config --global user.email "your email"

git clone https://github.com/jbahamon-uncc/itsc-2181-helloworld.git

cd helloworld

gcc helloworld.c -o helloworld

./helloworld
