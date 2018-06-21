step1: 
//compile a hello.exe ,run in widows
mvn clean install -P windows   

//or

//compile a hello.exe ,run in linux
mvn clean install -P linux      

//then it will create a new folder gowork/src/hello/bin 
//and an executable file will be produced

step2:

//if in the windows ,it is hello.exe ,you can run hello.exe 
//if in the linux,it is hello ,you can run ./hello
//it will print hello world.

