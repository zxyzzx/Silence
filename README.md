# Warning

Creative Making —— Final project Weekly Record


Week 6：

My Work: selecting project themes, preliminary design proposals, progressive in-depth research, thinking about design direction

My project was inspired by my current state of life. I am concerned that people are sensitive to sound. Living alone for long periods of time, in a closed room, I feel disconnected from the world and all the silence and noise make me emotionally tense, which affects my mental state extremely. I looked on the internet and found a lot of advice from people with similar experiences, such as keeping flowers and going out to see cute animals. My initial design was more in terms of problem-solving, thinking in terms of how to relieve emotional stress, hoping to make something healing and companionable, cute things are always healing.

I created some ideas, and then I made a sketch for my idea:




Flow Chart:

![image](https://user-images.githubusercontent.com/119873123/206622856-a310e0e3-7fac-493e-b478-2fcea8e3d735.png)

Idea description:

The project needs cute housing to make it look a bit more approachable or quirky. When someone passes by, the distance sensor detects the position information, and the signal is transmitted to the motor to make some funny body movements. If the person is in a stationary state, probably working or studying, the sound of tapping the keyboard or writing is played through the buzzer or speaker, as if someone is studying with you, giving the feeling that "I am not alone all the time " kind of atmosphere.


Later I did some more in-depth research on the subject and I found that humans are sensitive to sound. I was reminded of a psychological experiment called the Soundless Test. The researchers dissected the nature of this 'fear of silence' that we are born with. The reason silence is so frightening is partly because it subconsciously means that "something big is going to happen" and creates a sense of anticipation - or anxiety - depending on what you What to expect. Without auditory cues to remind you of what is happening, it seems that anything is possible. Is there anything more frightening than that? Maybe phonophobia or acoustophobia?
For example, horror films like to use silence to create a scary atmosphere. This probably stems from an instinct of fear of silence in people themselves. This somatic source is explained as "a sense of unknown and ungraspable fear of the surroundings".


Week 7:

My Work: Reflect the new design ideas, thinking about suitable inputs and outputs, idea sketches, drawing circuit diagrams

Based on further research I rethought the design direction again

Brainstorming：
![brain Storming](https://user-images.githubusercontent.com/119873123/206624805-f4206c74-bdca-43ab-8597-da30b361c8ba.jpg)


Sketch：


Concept：

Selecting the appropriate inputs and outputs according to my ideas.

![图片2](https://user-images.githubusercontent.com/119873123/206626181-f08c6a3e-0b87-4648-9ac4-6e14186a32bd.png)


Stage 1: Facing a sudden silence, will you choose to move away or get closer?
I chose to use an ultrasonic sensor for controlling MP3 music playback by distance. The music will keep playing when the person is not close to the box. If the person moves closer to the sensor, the music will stop playing. I wanted a sudden change to mobilize the emotional rising and falling of the interactor.

Stage 2: When facing silence, you expect what?
I chose to use a button to control the motor. The interactor can place their hand on the cardboard and when the program runs to the second part, the box will make a thin sound, using cotton thread to connect the motor to the hand-shaped cardboard. The motor rotates, pulling the interactor's hand toward the inside of the box. If you want to move away from the box, you need to press a button to make the motor Stop, instead, the motor will take you to explore the deepest part of the silence.

Circuit diagram：

![电路图2](https://user-images.githubusercontent.com/119873123/206626356-200b42f1-33c3-4828-acdc-a183f5a9e741.png)


Week 8:

My Work: Interaction flow, coding part, code testing, soldering, program change iteration, and writing text.

Some surprises：

1. About resistor:

After assembly, I found that the speaker had a loud noise of current, which for a while made me think it was a problem with my code because I found that it would sound whether it was close or far away. Then I searched on the web and saw somebody share that it needed additional resistors. I tried it later and the speaker played the sound just as normal and I was so excited that this problem was solved.

2. Error on Arduino board: 

![image](https://user-images.githubusercontent.com/119873123/206633634-ef684bc7-fa17-42a2-b0bb-edfe764993b9.png)

After testing successfully, I tried to edit my code but suddenly when I uploaded the code it suddenly showed compile error and shows the port could not be found on the software, I was so confused I don't know what happened and I tried to retransfer the circuit to the breadboard also unsuccessful, so I asked the teacher for help. After we looked into it we ended up thinking that the soldering might be shorting out the circuit.

3. Problems with soldering:

At first, I don't know that the solder board needs to distinguish between front and back, when I soldered some of it and showed it to my classmate, she told me that I had soldered it backward, so I removed it and soldered it again.
Solder is very testing, when I add a lot of material then it is easy to short circuit; when I add very little material then the wire is easy to come off the solder plate, and it took me a long time to fix it.

4. Circuit connections:

The power supply voltage is not sufficient to require an additional power adapter.


Some processes:

![e49588e987752ad00834b1a9278cd2d](https://user-images.githubusercontent.com/119873123/206635368-b8989c35-a9cc-402a-a09b-016504832213.jpg)

![731df3cbe4c678157856a7c5774d8ca](https://user-images.githubusercontent.com/119873123/206634494-9849dd10-d23f-461d-92cd-bb3181cc2778.jpg)

![e49588e987752ad00834b1a9278cd2d](https://user-images.githubusercontent.com/119873123/206634929-1ccccd5d-17a6-4f6f-bc96-b77f69b5aeec.jpg)


Week 9:

My Work: code testing, housing production, recording video, writing text

About the appropriate housing, I made a simple model to determine the size of the housing, because I wanted it to be a very deep box to match my interaction scheme.
In the end, I chose 24 x 12 x 35mm, with an opening (length x width) large enough to put a hand in.

Visual scheme:

I will use cardboard to make a pleated effect, wrapping it in layers around the outside of the box, with the cardboard stacked to make the box resemble a sponge-wrapped soundproof chamber.




Summary (challenges and gains)：

About the challenges, I really think the process was full of challenges, not only needed to learn the code knowledge during the project. The circuit connections afterwards also need a lot of patience and care. The housing also required full use of hands-on skills. Probably the most challenging part for me was the code, for example some of the symbols took me a long time to understand them. But in the end I managed to complete them, whether by asking my classmates or my teacher for advice.
During this course I not only gained knowledge of code and circuits, but also gained friendship in the lab. Although each student was preparing their own final project, but we discussed our experiences with each other during the busy time, for example: someone spent a long time checking the circuit and finally found that it was a soldering short circuit; someone found that the speaker often did not work and found that it needed added resistors to match the circuit work; some people were not proficient in code and asked teachers and classmates for advice on their problems. Throughout this some of the experience even kept passing on, I gained knowledge about soldering boards from one girl and I passed it on to another student when someone asked me about it. Being in the lab is busy and fulfilling, it's an amazing place! I really like here.

