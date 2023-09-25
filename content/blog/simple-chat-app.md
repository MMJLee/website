{
   "title": "Building a Chat App",
   "author": "MyungJae Lee",
   "description": "MJ's experience building a simple chatting web app from scratch.",
   "date": "2023-09-16T16:16:29-05:00",
   "draft": false
}
This was my first project involving WebSocket protocol, or rather, [Socket.IO](https://socket.io)'s interface for WebSocket protocol. I used Node, Express, and React and deployed it using Cloudflare and Fly.io. Socket.IO's documentation made the development process a breeze.  
&nbsp;

You can use it by going to [chat.mjlee.dev](https://chat.mjlee.dev). Enter any set of characters (except a forward slash) in the top bar where it says "join a room". Then press enter/return to navigate to that room. Then you can type in a name to be displayed in the chat, and press enter to join the room. You can press the clipboard icon to copy the room url to share with friends. Nothing is persisted.

If the slug is long enough, it can act like the private key of a cryptocurrency wallet, protecting your chat room from any unwanted guests.  
&nbsp;

I've written Python, Java, and Go backends, but never Node.js. You can't really call this project "writing a server", but I didn't have to write much to know that I wasn't a fan of the syntax.
I've always preferred strongly typed languages like Java. The code looks worse at first glance from the type declarations, but it's much clearer once you try to actually read it.  
&nbsp;

Since my professional software development experience lies mostly in backend & devops, the CSS did stump me a bit at first. React was actually really nice to work with, and I really enjoyed the way it handles state management. I still may implement MongoDB in the future and allow the user to choose whether to persist the messages or not.  
&nbsp;

Demo [here](https://chat.mjlee.dev) and code [here](https://github.com/MMJLee/chat). 
![sample screenshot of https://chat.mjlee.dev](/images/blog/chat.png)