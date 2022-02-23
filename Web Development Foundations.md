# Web Development Intro and Basics
### What do web developers do?
Web devs build and maintain websites
* Often work for clients to get a product onto the web. 
* This work involves collaboration between teams, devs, and the client itself.
* Work could involve **Front end, back end, or full stack** web development.

* **Front end** refers to the stuff you see on the browser. Devs use HTML, CSS, JavaScript, and their frameworks to present their content. 
* **Back end** is basically the backbone of the page or app, which lives on the server side of things. Devs use programming languages such as Java, Python, and Ruby to work with the data.
* **Full-stack** refers to the use of both front end and back end principles. 

---

### When asking for help from others
Asking well formed, thought out, and context based questions allows for higher quality feedback.
* Always provide your code and surrounding context. 
* Asking vague, conceptual questions will yield vague, conceptual answers.
* Provide as much context as necessary so that respondents can provide the most relevant answers while assisting you
* **Ask about the problem at hand** instead of just asking for a solution. You're actually the one who needs to be solving the issue as a learner. Ask for help on the specifics rather than just asking someone to fix it for you.
* Let people know what you've tried and what hasn't worked. This allows the respondent to help with your current iteration of code rather than giving you advice that would set you back several steps.
* Getting asked for more context is not something to fret about, respondents are simply trying to understand your request better and *want* to help!

---

**[Reference: How to be great at asking coding questions](https://medium.com/@gordon_zhu/how-to-be-great-at-asking-questions-e37be04d0603)**

* *(from article)* Explain the context. Explain the exact steps you took to produce the problem. Explain what you expect to see. Explain what you actually see,
* Provide the code that illustrates the problem. Isolate that code and make sure that it doesn't change by the time someone looks at it. 
* Make sure the code you share reproduces the problem. 
* Ensure that your code is written consistently. 
* Explain what you did to troubleshoot.
* Explain what you think the problem might be.
* Proofread your question
* Thank each respondent and inform them when the problem is solved so they don't waste any more time solving it.
* 'code' is how you include code into markdown.

**Quick tips for answering questions**
* Instead of answering the question, *guide* them to the answer
*  Help only when you know the answer for certain.
* Do not jump into the middle of someone else's conversation. This can be overwhelming  for the OP.
* Ask for clarification when needed. Also ask for live code where appropriate. 
---
### How does the Web work?
* Millions of nodes and servers are connected to one another via cable. Smaller cables connect these nodes to individual computers, thus, making the internet.
* This is *not* the World Wide Web, but rather, the infrastructure of networks that enables the WWW to function. The internet is the hardware/framework while the WWW is the *software* in a sense.

**How it works:**
- Individual requests for data are sent through regional servers, across the globe to where the data is stored.
- In order to avoid clogging the networks with whole, large files, the data is split up into smaller **packets**, sent individually across various routes, and reassembled once it reaches its destination.
- Once the packets arrive, the device shuffles everything into place and presents the data in its original format.

**Network basics**
* In order for one to have a network, you need at least two computers connected to one another, sharing information. 
* You can connect as many computers as you wish, however, it gets exponentially more complicated as you add more computers. For example, a 10 computer requires a total of 45 cables with nine plugs per computer. 
* To solve this, these computers can all be connected to a **router**, which functions to ensure the right message gets sent to the right computer on the network.
* With a router, that complicated network of 45 cables becomes much simpler with only 10 cables required - one for each computer. 
* A single router can only handle so many connections, so to scale this, we can then connect 2 sperate routers, each with their own network, to one another.
* Connecting routers to those routers allows for an even larger scale of networking. By doing this, we can scale networks infinitely.
* Utilizing phone and power lines that are run through a **modem**, we can use pre-existing phone infrastructure to connect our homes to the servers that run the internet.
* In order to send the messages from our network to the network we want to reach, we must connect to an internet service provider or an ISP. The ISP has specialized routers that connect to other ISPs which, in essence, makes up the internet.
* Computers use IP addresses to specify exactly which computer they are sending data to.
* Domain names are an easier way for humans to remember where they intend to send data, so these domain names are used instead of IP addresses. For example, google is the domain name for 142.250.190.78.
* The _Internet_ is an infrastructure, whereas the _Web_ is a service built on top of the infrastructure. It is worth noting there are several other services built on top of the Internet, such as email.
* **Intranets** are private networks that are restricted to members of a particular organization. These networks might contain internal docs, wikis, messaging boards, and admin tasks. 
* **Extranets** are very similar to Intranets, except they open all or part of a private network to allow sharing and collaboration with other organizations. They are typically used to safely and securely share information with clients and stakeholders who work closely with a business.
* **Web browsers** are programs on your computer that allow you to visit websites. These are different from search engines!
*   **DNS**: Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place. This is like looking up the address of the shop so you can access it. (Mozilla)
* **Component files**: A website is made up of many different files, which are like the different parts of the goods you buy from the shop. These files come in two main types:
* -   **Code files**: Websites are built primarily from HTML, CSS, and JavaScript, though you'll meet other technologies a bit later.
- *  **Assets**: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.
