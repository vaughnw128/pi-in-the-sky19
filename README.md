# Vaughn and Charlie's Pi in the Sky

## The Plan

### The Rough Idea
Our plan is to create a foam version of a clay pigeon, which houses a raspberry pi with an accelerometer. We are planning to launch the foam pigeon/pi assembly out of a normal clay pigeon launcher at a shooting range or somewhere out in the country. We are going to create the foam clay pigeon by making a silicon mold of a normal clay pigeon first, and then using an expanding foam to fill the mold. We want to make the clay pigeon out of foam so the pi will stay safe during the first flight. We are hoping the foam will absorb the impact of the fall and protect the pi, so we will be able to take measurements during the flight and recover the pi. Also creating a silicon mold sounds fun and interesting. In order to fit the pi into the foam pigeon, we are going to create a circular custom PCB board that will house our pi and all the components we need, such as an accelerometer, battery, LED, and perhaps some other additions. Once we have gotten some measurements and hopefully a succesful flight, we will launch the pi a second time and blow it out of the sky. 

### Expected Materials and Costs

| Item  | Source | Cost |
| ------------- | ------------- | ------------- |
| Raspberry Pi Zero W  | Sigma Lab  | $10.00  |
| LSM303DLHC Accelerometer  | Sigma Lab  | $7.95  |
| LP803860 LiPo Battery | Sigma Lab | $12.50 |
| Powerboost 500 Charger | Sigma Lab | $14.95 |
| Clay Pigeons | Field and Stream | $10.00 |
| Box to create mold | Charlie's house | $0 |
| Silicon Mold Kit | Amazon | ≈$35 |
| Expanding foam | Amazon | ≈$35 |
| Release Agent | Amazon | ≈$10 |
| Piezo Buzzer | Sigma Lab | ≈$1.50 |
| Custom PCB Board | Sigma Lab | ≈$5 | 
| Acrylic cover | Sigma Lab | ≈$3 |

### Projected Issues
One of the biggest issues that we project is the size and shape of the clay pigeon related to our foam replica. Ideally we would like to shoot our project once and recover it. Since we are using a normal clay pigeon launcher to launch our project, the size and shape must be very accurate to the real thing. This is difficult due to how small the pigeon is and it's shape. Even the small components we need to add may affect the pigeons flight, so we are hoping that creating a PCB to mount the components on will help us with our size concern and won't significantly affect the trajectory of the flight in comparison to a normal clay pigeon. Another concern that we have is the foam holding up to the stress of the flight. We are hoping to address this by buying an expanding foam with a higher density than some of the other options, so it will be able to withstand the pressure from the launch.
## Project Schedule Estimate

### Week of 8/26/2019
Planning period - Researching costs, materials needed, and planning out the project ahead for optimal results. During this time we will try to source some of the prototyping materials that we need. Aditionally, design will be started on the PCB.
### Week of 9/2/2019
Continue design on PCB, and try to get all wiring components working together and recieving data. Charlie will be testing out ideas with foam and silicone.
### Week of 9/9/2019
Field test with raw components in a foam football of some sorts. At this point hopefully start doing real tests on printing the PCB, and taking silicone castings of the clay pigeons.
### Week of 9/16/2019
Pour silicon mold
### Week of 9/23/2019
Pour foam and work on PCB
### Week of 9/30/2019
Get some foam models
### Week of 10/7/2019
PCB Tests/Plan done on fritzing
### Week of 10/14/2019
Finished foam models, work on PCB
### Week of 10/21/2019
Start putting things together, work on code
### Week of 10/28/2019
Code
### Week of 11/4/2019
Code
### Week of 11/11/2019
Code
### Week of 1118/2019
Code
### Week of 11/25/2019
Code

## Weekly Updates

### Week of 8/26/2019
This week we are finishing up our writeup of this plan on Github, and working on getting materials for our project. So far, we have purchased clay pigeons from Field and Stream, and Charlie is working on creating a box around the pigeon to hold the mold. Vaughn is setting up the pi and is going to start work on a custom PCB soon.

The dimensions of a standard clay pigeon are 108 mm in diameter and 29 mm tall. When creating a mold it's optimal to have at least a 1 inch buffer between the edge of the model(in this case the clay pigeon) and the edge of the mold. For this reason, the box around the clay pigeon should be around 55 mm tall with a 140x140 mm base. Charlie is planning to construct this box out of wood and then bring it in for the molding process. 

Using the size of the box we can calculate the volume inside and subtract out the space occupied by the clay pigeon. This will give us the amount of silicon we need for the mold, and from there we can also find the amount of foam needed to fill the mold.

### Week of 9/2/2019
This week Vaughn is working on setting up the components of the pi while Charlie is working on the mold. 

I have decided to create the mold using a two part block method, first doing half of the mold, waiting for it to cure, and then pouring the other half. This will let us get the shape perfect and all of the details that help the pigeon fly. I will start constructing the box for the mold tonight, and hopefully get the mold done soon. 

### Week of 9/9/2019
This week our plan is to work on the mold and the software for the pi. So far, Charlie has modeled and laser cut a box for the mold to be formed in while Vaughn has been putting together the pi hardware so he can whip up the code. Hopefully this week Charlie can get the silicon and get the mold prepared to be filled, and next week we'll probably be ready to fill it. Quick update for the end of the week: Vaughn has decided to create a custom PCB because it will help organization and Charlie has just ordered the silicone materials needed after using this week to construct the box for the mold. Next week Charlie will start the mold once the materials come in and Vaughn will continue his work. The extra steps we are taking might add some time to our schedule but as of right now we believe we will still finish on time.

![Resized952019091695110550](https://user-images.githubusercontent.com/47390860/64971380-9c813f00-d875-11e9-9916-dc486f722c41.jpg)

![Resized952019091695110553](https://user-images.githubusercontent.com/47390860/64971374-9ab77b80-d875-11e9-9aec-5a67aa2cc14f.jpg)

### Week of 9/16/2019
Quick update: Over the weekend the silicon materials came in through Amazon but the release agent for the mold and part have not arrived yet. That means that today all I can do is set up the parts for casting and hopefully the release agent will be here tonight so we can start molding on the block day. The images shown above this text are the laser cut box(held together by string so we can easily remove the box pieces once the mold is finished), and the clay pigeon we will be molding with the tiny piece of wood thats going to hold it up so we don't have to do a two piece mold,
Update 2: Today Charlie was the only one here because Vaughn was sick but I went through with the molding process anyways because the release agent had come in. These are my thoughts after just pouring, it hasn't set yet because it has a cure time of 75 minutes. I thought it went well but the amount of silicon we eneded was just a tiny bit more. For now, Charlie has to research the foam and purchase that, and then deal with the mold once it has cured. 

![IMG_20190917_113007139](https://user-images.githubusercontent.com/47390860/65056498-f39f1680-d93e-11e9-9f7d-6d20b6b292c9.jpg)

![IMG_20190917_113012626](https://user-images.githubusercontent.com/47390860/65056483-ea15ae80-d93e-11e9-890b-bb2bf0c13412.jpg)

The above images are showing parts of the molding process. The bucket was where I mixed the 2 part solution and then I proceeded to pour it directly into the box, where the mounted clay pigeon was set in place. There is a little bit of spillage because our box was not super tight, the string had loosened a bit, but it was mostly pretty clean. 

### Week of 9/24/2019
It is Tuesday the 24th and the mold is done. It looks super cool and is very fun to play with, and now all Charlie has left to do with the mold is purchase the foam material and pour it, which means the molding process will be done this week hopefully. Here are some pictures showing the finished process.

![IMG958986](https://user-images.githubusercontent.com/47390860/65524726-46874980-debc-11e9-8e42-7d80711deee7.jpg)
![IMG958983](https://user-images.githubusercontent.com/47390860/65524729-47b87680-debc-11e9-91c3-6483b3b558d1.jpg)
![IMG958984](https://user-images.githubusercontent.com/47390860/65524734-48e9a380-debc-11e9-8a2d-fa98ac94d61f.jpg)
![IMG958985](https://user-images.githubusercontent.com/47390860/65524735-49823a00-debc-11e9-885c-eb43fda56f99.jpg)

![IMG_20190927_112928855 (1)](https://user-images.githubusercontent.com/47390860/65781879-79c71400-e11a-11e9-9e76-ad0d58b98f46.jpg)
![IMG_20190927_112935191](https://user-images.githubusercontent.com/47390860/65781883-7af84100-e11a-11e9-9272-b425e436d1e4.jpg)

Here are some pictures showing the molding process and a failed foam mold. The foam has been hard to work with so hard, but we have so much material because the foam expands to 10 times its liquid size that we are able to trial and error a lot. Currently, we just poured our try for the day, and we're hoping that it turns out well otherwise we will have to continue pouring next week.

### Week of 10/07/2019
Currently the foam pigeon and cover to hold the pi and pcb in place are complete. Vaughn is working on the pcb and after that all we have to do is put the project together, finish the code, and we're ready to go. Here are some pictures of what we have right now and some of the molding process as well:
![IMG_20191007_110233751](https://user-images.githubusercontent.com/47390860/66323838-6a9e4e00-e8f2-11e9-9066-c43b8c58ad0e.jpg)
![IMG_20191001_120734557](https://user-images.githubusercontent.com/47390860/66323844-6d00a800-e8f2-11e9-80a4-4944008554f8.jpg)
![IMG_20191002_123300187](https://user-images.githubusercontent.com/47390860/66323848-6f630200-e8f2-11e9-895b-14a334624760.jpg)
![IMG_20191007_110240146](https://user-images.githubusercontent.com/47390860/66323854-725df280-e8f2-11e9-8b1b-8f3fb01ccf4a.jpg)
![IMG_20191007_110248015](https://user-images.githubusercontent.com/47390860/66323855-725df280-e8f2-11e9-9346-f2766d63f2ca.jpg)
![IMG_20191002_123247213](https://user-images.githubusercontent.com/47390860/66323856-725df280-e8f2-11e9-8e8b-32e3324a5777.jpg)
![IMG_20191007_110236804](https://user-images.githubusercontent.com/47390860/66323858-72f68900-e8f2-11e9-8851-a47652216648.jpg)
This week we are trying to finish up the PCB. So far we have cut one board that isn't quite right, so Vaughn is quickly editing his design and then we will try again.

### Week of 11/6/2019
This week is a short week because of the small halloween break we had, but we are currently trying to finish up the code and make the pi tell us when it is at the top of its flight. The foam pigeons are pretty much totally complete, and the PCB is complete as well. Here are some pictures showing the finished foam pigeons as well as the pcb with everything on it.
![IMG_20191106_110543416](https://user-images.githubusercontent.com/47390860/68315374-ad844a80-0085-11ea-88df-95f73fed77c3.jpg)
![IMG_20191106_110433068_BURST000_COVER_TOP](https://user-images.githubusercontent.com/47390860/68315379-ae1ce100-0085-11ea-980a-b8496b3682b2.jpg)
![IMG_20191106_110523779](https://user-images.githubusercontent.com/47390860/68315382-af4e0e00-0085-11ea-8a83-90f8070c010c.jpg)
![IMG_20191106_110539339](https://user-images.githubusercontent.com/47390860/68315385-b07f3b00-0085-11ea-9190-76ba5dbbdfb4.jpg)
![IMG_20191106_110437254](https://user-images.githubusercontent.com/47390860/68315389-b1b06800-0085-11ea-860e-f3fb7f4121e7.jpg)

### Week of 11/14/2019
This week we are working on coding, specifically the part where the pi will tell us when it reaches the vertex of its flight. This has been fairly problematic for us, so we are trying to get assistance from Shields and other students to help us out. 

### Week of 11/18/2019
This week we are continuing our work on code. Right now we have the acceleration, but we have to figure out how to use that to find when the pi is at the top of its flight path, and do something at that moment(probably turn on a light or play a sound).

### Week of 11/25/2019
This week we are continuing our work on code. We are planning to remake the PCB and add a Piezo buzzer that will activate at the apex of the flight, and remove the LED.

### Week of 12/2/2019
We're continuing code.

### Week of 12/9/2019
Continuing code.

### Week of 12/16/2019
Continuing code, break soon.

### Week of 1/3/20
Got back from break, picking things back up with code. Trying to finish the Rieman sum, theta calculations are already good.
