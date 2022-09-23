# ARDUINO-BLUETOOTH-CONTROLLED-SMART-IRRIGATION-SYSTEM
HERE in this article I am going to show how to make a smart irrigation system at home. This is very easy to make and ofcourse its a prototype project which could be modified according to our need. I have made this basically for the begineers or the intermediates. This is an ARDUINO BASED project which makes it user friendly and if you are looking for a project to show some where like science exhibitation, final year college project presentation, environmental science project, agricultural project etc in several field then this is really a good project that you may try. Mkaing cost for this project is also very low.

![MTI2](https://user-images.githubusercontent.com/79990158/191947961-f8d24723-ca6b-4067-9a2b-fb95c8d89e23.jpg)

### WHY AUTOMATIC IRRIGATION SYSTEM IS NEEDED

#### The benefits of automatic irrigation are:
- reduced labour.
- timely irrigation — plants being watered when needed.
- management of higher flow rates.
- accurate cut-off of water compared to manual checking.
- reduced runoff of water and nutrients.
- reduced costs for vehicles used to check irrigation.

### PARTS OF THE PROJECT

To make and understand it easily we have splitted this project into two main parts.
- MECHANICAL Part
- ELECTRONICS Part

for better explaination we have divided our ELECTRONICS Part into
- Circuit and PCB 
- Assemble the electronics components 
- ARDUINO coding

### MECHANICAL PART
 Here in this part we will need some PVC sheet to make the chassis, 4 TT gear motors with wheels, 1 submersible pump, one coldrinks can which is completely optionnal. you may use anything elese to make the water tank. This is considered as the easiest part of this robot. All you need to only cut the PVC sheet and assemble all the components together in a proper way. Here i have attahed some pictures on this.
 ![Screenshot (34)](https://user-images.githubusercontent.com/79990158/191951063-c64f127d-09fa-46f7-9f12-24857179f034.png)
![Screenshot (36)](https://user-images.githubusercontent.com/79990158/191951079-7675be2b-351c-430a-ae5b-0844736bb921.png)
![Screenshot (37)](https://user-images.githubusercontent.com/79990158/191951103-9de26dad-0713-46bc-b9ff-9ecbe78e3245.png)
![Screenshot (62)](https://user-images.githubusercontent.com/79990158/191955399-d24b8c4c-f988-438f-9d27-9fe79101073c.png)
![Screenshot (66)](https://user-images.githubusercontent.com/79990158/191955426-4429843c-82fc-4107-b62b-be0a1f540e14.png)


Here i have used 60rpm TTgear motors but you may vary the rpm according to your need. But one tips i want to share that, lower rpm motos are easy to control & they could be shown easily in any resentation.
Thats it for this part. now we will move to our next part which is ELECTRONICS PART. Here we will directly enter into the circuit and pcb making part. This could be littlebit tough if you are a fresher in making electronice project but i will explaint is as much easier as possible.

### CIRCUIT & PCB MAKING 

Here I have attached the circuit or the connection diagram which is very easy to understand and make. Please follow this diagram when you are going to make this project. 

![diy arduino bluetooth controlled irrigation system](https://user-images.githubusercontent.com/79990158/191955638-8dd73803-5762-4cb2-9120-8351b8ed244c.jpg)

This project will work or perform same with or without making pcb but I have made PCb boards for this project. Actualy not only for this, I always do prefer making any project using Customized PCB boards. There have obviously some advantages of making any project using PCB boards. like
- Compact Size and Saving of Wire.
- Ease of Repair and Diagnostic. If in case of any damage, it's very easy to check and replace the particular failure components. 
- Saving of Time. 
- Immune to Movement. 
- Tight connections and Short Circuits Avoided. 
- Low Electronic Noise. 
- Low Cost. 
- Reliability.

So i always make PCB BOARD for my every project. As I have already mentioned before I have already attached a circuit diagram with this article so please download that before you are going to connect all of them together. In my case, I have made a customized PCB board from JLCPCB to skip a few steps of wiring and make an easy connection between all the components.$2 for 5pcs PCBs, PCBA from $0, Register to Get Free Coupons here: https://jlcpcb.com/IYB. I really liked the PCB Boards as they are very high in quality.

![Screenshot (9)](https://user-images.githubusercontent.com/79990158/191957722-0278b406-2e23-49d5-8392-0730bdd3b405.png)![Screenshot (10)](https://user-images.githubusercontent.com/79990158/191957763-87704c04-f323-469f-8b61-63458498ea0f.png)
![Screenshot (13)](https://user-images.githubusercontent.com/79990158/191957855-13a87242-5d37-4aec-a42a-83b2282273a9.png)
![Screenshot (14)](https://user-images.githubusercontent.com/79990158/191958005-598234cd-9077-47ae-8a3b-146874a56a14.png)
![Screenshot (15)](https://user-images.githubusercontent.com/79990158/191958022-7a4e32a0-6606-41d2-bcae-c71efcedfd14.png)

### ASSEMBLE THE ELECTRONIC COMPONENTS

Noow we will make all the components together. But before that please make sure that you have gathered all of them correctly. Here i have enlisted the components and also provided their pictures for your referances. Hope this will help you to make this easier.

#### SO THE COMPONENTS THOSE WILL BE NEEDED ARE 
- ARDUINO NANO WITH CABLE
- L298N MOTOR DRIVER
- HC-05 BLUETOOTH MODULE
- M4 DIODE
- RED LED
- 78M05 VOLTAGE REGULATOR
- 220uF CAPACITOR
- TERMINAL BLOCKS
- HEADER PINS
![Screenshot (50)](https://user-images.githubusercontent.com/79990158/191959780-90fc362f-d9c8-45e0-a8e3-830e1a1fec73.png)
![Screenshot (45)](https://user-images.githubusercontent.com/79990158/191959912-a9854137-af6e-4199-88b7-e78a2673847f.png)
![Screenshot (49)](https://user-images.githubusercontent.com/79990158/191959830-0e323c5f-60ff-44d2-b29c-49db9da58c44.png)
![Screenshot (46)](https://user-images.githubusercontent.com/79990158/191959905-a02f52a3-de6c-4903-94f1-4662026d0e43.png)
![Screenshot (48)](https://user-images.githubusercontent.com/79990158/191959858-70b73db4-e125-48f7-95f9-523a06771360.png)
![Screenshot (47)](https://user-images.githubusercontent.com/79990158/191959876-9c8fbb17-de9a-43d8-a678-61574215ea1c.png)
![Screenshot (51)](https://user-images.githubusercontent.com/79990158/191959813-aa3b4825-16bd-4867-80b3-b1a04a547280.png)

Now please assemble all the components together to complete the project. this is very easy to do if you follow the simple connection diagram. But if you have any doubt on this you may watch this video for better understand
https://www.youtube.com/watch?v=LxMCDFM3j0s

![Screenshot (52)](https://user-images.githubusercontent.com/79990158/191961119-afac772a-cebb-499c-b739-e49d1ca62248.png)
![Screenshot (53)](https://user-images.githubusercontent.com/79990158/191961145-8a959ff4-7ae8-4d5a-bb3d-bded8cdd9566.png)
![Screenshot (58)](https://user-images.githubusercontent.com/79990158/191961393-b8f9bec5-a7d3-4b69-b8bc-e29f9bd1a2e3.png)
![Screenshot (55)](https://user-images.githubusercontent.com/79990158/191961305-bcb9fb2b-7b2f-4083-b7d6-f6f1fe8c9489.png)

after assemble all the electronics part together only one thing will be left for us which is ARDUINO CODING. Trust me this part is realy very easy as compared to these previous parts. So lets finish it...

### ARDUINO CODING

First of all you need to download Arduino IDE in your system which is a completely free software for all the users. You can easily download it from their official website. Then download the necessery libraries like- Adafruit Motor Shield library, Dabble, etc and then you have to select the correct boards and ports. Here in this case we are using arduino nano so you have select arduino nano & for port you have to select the port that shows in the software after connection your Arduino Board with your system. It will be some thing like com port 3, com port 7, com port 4 etc and so on. 

![Screenshot (60)](https://user-images.githubusercontent.com/79990158/191966052-4eb57393-758a-41e7-9512-b4a33dc1a2aa.png)

Then you need to download or copy the given arduino code and pest it or open it and upoad it in arduino nano.

PLEASE don't forget to disconnect the hc-05 bluetooth module while uploading the code.
![Screenshot (59)](https://user-images.githubusercontent.com/79990158/191965992-92011ab5-9fb3-4c82-86bf-d0e87c68d386.png)

Once you have done all this, only one last part is left which is giving power to your robot. Here i have used one 12v diy rechargeable li-ion battery. which i have made using 18650 li-ion batteries. This is also very easy to make and please click on the link if you want to know How to make 12v rechargeable li-ion battery at home.
https://www.youtube.com/watch?v=5nu53428TA8
![Screenshot (64)](https://user-images.githubusercontent.com/79990158/191970952-4fec01b4-dd45-4197-a314-d171fbd5f7e9.png)

## CONNECTING VIA BLUETOOTH

After everything, finally we have to connect the robot with our android phone via bluetooth. There have so many Android app easily available in play store. I have downloaded one of them and installed it in my Android phone. Then I have turned on the robot and serached for HC-05 bluetooth. then they will as for the passward. Most of the cases it is '1234'. then it will connect successfully with the robot. then open the app and run your bot.

![Screenshot (65)](https://user-images.githubusercontent.com/79990158/191972170-f9d67c91-2dfe-4038-ab35-2fb13d0f362e.png)
