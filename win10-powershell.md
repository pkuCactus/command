1. Create the soft link like ln in linux
    > cmd /c mklink /d linkname target (required the administration previlige)
   
2. show the enviroment variable
    > ls env:
  
3. get a specific enviroment variable x = "XXX"
    > $env:x="XXX"
  
4. delete a specific enviroment variable x
    > del env:x
   
5. update  a specific enviroment variable x to "YYY"
    > $env:x="YYY"
   
6. add something to an exist enviroment variable x
    > $env:x+="xxx"
