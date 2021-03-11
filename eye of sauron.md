                In this challenge we are provided with a .NET application which takes input from the user and if the input is correct, we shall pass else we will not!
                On running the executable we can see it has a gui!

[sauron](https://user-images.githubusercontent.com/59394569/110738037-a05e0980-823f-11eb-967a-5445e6072e98.png)


                As we do not have the code, we need to decompile this exe file in order to decompile and see the code.

                I used dotpeek from jetbrains to decode the file and found the methodology in the text password field being as follows: 

(https://user-images.githubusercontent.com/59394569/110777122-d320f580-8271-11eb-8a06-f70be0ca9647.png)

                          Simple but tricky right! We have to find all tokens then reverse them.

(https://user-images.githubusercontent.com/59394569/110777614-5f331d00-8272-11eb-9d68-cf2ac0cb20af.png)


             i compiled them and used a site (http://spellbackwards.com/) to reverse..I know most of you will use the 'rev' command on linux terminal




                                          I like simple work xD!!!
                                          
![giphy (1)](https://user-images.githubusercontent.com/59394569/110780601-ed5cd280-8275-11eb-9de9-e6390c6fc136.gif)




