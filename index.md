## Project 6 Web Page for David Foster

This is the web page for project 6, to show off the Seam Carving program.

## Picture of Me
Here is a picture of myself, David Foster
![Image](https://cdn.discordapp.com/attachments/268691482716667916/784624302267039774/20201204_223614.jpg)
## Good Case
When ran on a simple image like a barn on a background of sky, the program was very easily able to carve seams from that part, leaving the barn itself intact. You can see these results below.
This is the original image 500 pixels wide and 332 pixels tall.
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784627447915610112/barn500.jpg)
This is the new image 322 pixels wide and tall.
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784627446401466378/barn332.jpg)
There are almost no visible artifacts.

## Bad Case
When ran on an image featuring human faces, any distortion is immediately recognizeable. Here is several images featuring a crop of the famous Judith Beheading Holofernes oil panting by Caravaggio.

This is the original image, 478 by 478
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784628054621552650/j478.png)

This is the image reduced to 400 by 400. As you can see almost all of the detail remains intact, wit hsome black space culled by the algorithm.
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784628059348140072/j400.png)

This is the image carved down to 300 by 300. Artifacts have become visible in the woman's face, yet the face to the right still seems fine.
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784628057628868648/j300.png)

The image is now shrunk to a tiny 200 x 200 and both faces are heavily artifacted. Poor guys
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784628056379359279/j200.png)

And just for fun here is the image shrunk down to a miniscule 50 x 50. It is completely unrecognizeable as the original.
![Image](https://cdn.discordapp.com/attachments/749355731253198868/784628054650781696/j50.png)
