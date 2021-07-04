# Real-time learning support system

## Description
<img src="https://github.com/ayk24/learning_support_system/blob/master/doc/app.png" width=80%>

In this figure, the client side (students) is being taught math problems by the server side (teachers).
  
Students can send not only the text but also the image to teachers so that the teacher can respond to difficult questions.
Teachers are also able to explain the problem with diagrams.
If you are unsure of the answer, you can exchange a message or send the image again.

Furthermore, the same operation can be achieved when multiple outlets are connected.

## Features
- Uses its **own variable-length packet**s and is designed to combine **type** and **data**.
- **Packets(send to the server)**: Be broadcasted to all clients, and that is how the communication is achieved.
- **Type**: paint, text, and image. Each type includes the coordinates, color information, and user names in the packets.
- **Drawing**: Be adjusted by adjusting the interval between the two coordinate acquisitions, which is necessary for a straight line drawing, so that the effect is small and the curve looks smooth.

## Requirement
- Visual Studio 2017
- .NET Framework 4.7.2
