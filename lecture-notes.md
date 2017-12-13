#Evening Lecture Notes
NODE- connects back-end work and front end work

NPN: Node Package Manager
This is how we install brew node and other node packages through our terminal. They are external resources like libraries and templates we can download into our local drive

# npmjs.com
great source of libraries/templates to install

#56 minutes -to one hour watch video
#3:15pm-3:20pm 
time stamp for npm terminal coding
this should be in beginning of pt 2 lecture
#325 break down of node crazy shit
global [circulrar] means you have a thing is connected to an other thing connected to the thing you are on...hella confusing

#https://nodejs.org/dist/latest-v9.x/docs/api/
SOURCE of what scott did breaking down the node shit

"cannot find module express" error mesage in terinal means you didnt install the package

modules- is the key term for "chapters" of the segments in the library you see on the side bar when you launch the library from the URL source above

#npm i "package you want to download"
Example: npm i express
^^^ this is what i did into my codefellows so all my files can use npm
install this into every single project so your app has a direct resource for the libraries/packages you are using

#npm -g ls --depth=0
this is how to see all the packages ive currenty installed in the terminal. This is similar to using git status or something ya know?

#part 3 demo code of using express
express allows us to send a request server which will then validate the request and see if theres an end point of the request to reply to. Like a navigation guide or traffic cop/ROUTING is the actual term for this part of the process

app.use(express.static())... this will open all the express modules you can input. aka listening for requests to come in

app.get(endpoint, callback)
app.get('/', (request, response) => {

})
app.get.('/hello', (req, res) => {

})

app.get('/bye', (req, res) => {

})
// app.post()
// app.put()
// app.delete()