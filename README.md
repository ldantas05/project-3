# project-3
sprint 1

For part of sprint one I recreated step by step the zoom-clone video by Web Dev simplified https://www.youtube.com/watch?v=DvlyzDZDEq4&ab_channel=WebDevSimplified with linked repository https://github.com/WebDevSimplified/Zoom-Clone-With-WebRTC this particular iteration solves the problem of both videos in localhost not appearing and allows for a resize in the video grid between 240,480,720 and 1080p. Future iterations will refresh the image as well as implement a way to resize only the desired screen.

#Requirement

install nodejs as well as peerjs. 

#Launching

To launch type in terminal:
npm run devStart

in another window type:
peerjs -port3001

Now open a browser window and go to http://localhost:3000/ , copy the link and paste on another tab, you should be able to see both videos with the buttons. Clicking the button on one side will not change the resolution in the other side.
