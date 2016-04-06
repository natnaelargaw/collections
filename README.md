# collections
## How to use Simple Video Streaming code
##Considering you are using VLC 2.2.2 or above
1. Open VLC Media Player
2. Click on Media --> Oper Capture Device
3. Click on Capture Device
4. Select "Direct Show" from the first dropdown menu
5. Select your video capturing device from "Video Device name" Dropdown menu
6. Select your audio recording device from "Audio Device name" Dropdown menu
7. From the play dropdown menu at the bottom right, select stream
8. In the new windows click next
9. In the New destination Dropdown menu, select http
10. click on add and alter the port "default is 8080" and the path
11. click next
12. select "video- Theora + vorbis(OGG)" from profile dropdown menu
13. click next then stream
In your html page alter values for IP, Port and path. For example, "192.168.1.44--> your ip", 8081--> the port that u used during stream config and "test --> the path that u gave it to ur stream destination."
