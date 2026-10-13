# Portfolio_JobSearch_Analytics
This project's goal is to serve as a showcase of my skills and knowledge in various aspects of the programing field as well as the technologies and tools being used in the industry. The project shall combine several small docker container modules to form a software.

# Tools:
Use tools such as git & github, docker, kubernetes (at a later stage) to better understand how to hone the tools while working on a project, and gain experience and in each of these tools.
 - Git & Github - manage the repository and utilize githubs built-in tools to manage the project's pacing, planning and progress.
   - Git  -
   - Git  -
   - Git  -
 - Docker - Separate each piece of code\script into a standalone atomic module. Each such module shall serve as a docker container.

# Languages:
The project will be written in multiple programing languages in order to gain experience in programing languages such as: C , JavaScript, Python, Java, Node.JS.
- Node.JS - for managing Google API's
- Python - for data analytics
- JavaScript + HTML (& CSS) - for a simple frontend design
- Java Spring - for backend.
- C - mainly to practice on a low-level coding language to get a better grasp for the concept of memory management.

# Architecture\Development\Micro-services
Practice and reflect real-world use-cases for cloud computing and micro-services as well as learning how hosting and network-traffic work.
- Running the project on localhost (at first)
- Host and deploy the project on a platform
- Deploying and learning selfhosting with Ngin-X

The project shall be written both on a Linux environment as well as Windows.
The project will involve AI to serve as a bridge between code and unstructured data.

# The project plan:
# Container #1 - Gmail Integration:
- Pull incoming emails and forward them as a json object to the next docker image.
- Label emails (?) - Not sure if\how I'll use this, yet. Probably will, but I'll figure it out later.
- This container shall be written in either Node.JS or App Script. I want to get some experience in Node.JS to have yet another language in my arsenal.

# Container #2 - AI Integration:
- The data passed from Container#1 won't be persistent. Each job offer\listing has its own description and details.
- Use a LLama model I converted from the original meta weights, to take the json and create Json objects based off-of parameters I'll define to it using prompts.
- Combine an mcp server at this point just to gain some experience in mcp servers as well. The idea is to have the AI gather the data and use functions from an mcp servers to have the json built by code.
-
-





- Rephrase all the entries taken from my post to fit this readme.
-
-
-
-
-
- I know I can just instruct the model to write the json, but its a bit of an old model, so performance won't be as good as other models, and also, I'd rather have a mundane, but simple, task be performed properly using solid code rather than the AI do it, because it both better guarantees no errors\AI-mess-ups as well as lessens the load on the context adn cache.

The code shall be written in C, as I want to gain better control and understanding of the C language. The functions will (probably) be - write to json, save to json array, merge jsons, with the idea being - practicing struct and memory management as well. Not quite sure how though, so, I'll appreciate it a lot if someone well versed in C could provide their perspective in the matter😅

The model is going to run locally on a BC250 I have. I want to route the traffic from and to it. Again, local host at first, then self-hosted... somewhere... (eventually.... I hope....)

Container #3 - JSON to CSV:

I'll be honest - I don't truly know what am I thinking here... The idea was to transfer the JSON array from Container #2 and use C to convert the JSON to CSV and store in a DB (not quite sure which yet either. Would like to hear suggestions as well as the reasoning behind them).

The plan is to also handle usecases such as "same workplace, but different submitter\listing" and practice a bit of SQL or maybe NOSQL.

This container is mainly for practice and a bit of dabbling in Database operation (as well as to make my life a bit of a living hell more than it is currently so I push myself a bit😁). Open to suggestions\advice.

Container #4 - Data Processing:

With the help of python - fetch data from the Database and process the data using stuff like pandas, mattplot and everything else I haven't touched in 2 years 😔

The plan is to present some basic data analysis about all the listings, such as which in which region are jobs searched for most, how many jobs are searched in total this month\day (maybe even allow the user to choose some filters. The action itself shall happen in the front+backend, but data processing shall happen in advance in this step?), How frequently does a workplace post listings, etc.

Container #5 - Webpage frontend:

A basic webpage to show the data processed in the previous container (#4).

The page shall use basic HTML, CSS and maybe a bit of JS. (Should I use React \ Swift? I am not familiar with any of those at all... besides, I am not really aiming for any frontend jobs...)

Not much to state here.... just some buttons and tables... maybe a small introduction paragraph to introduce myself and my credentials and contact methods?

Container #6 - Webpage backend:

Backend stuff... I guess...

Going to use Java Spring\Boot for this one. Used Java Spring in the past and so, I have a little bit of experience (and a whole bunch of horrible memories of mental breakdowns 😥)

Container #7 - Hosting:

A docker image of Ngin X for running a self-hosted server. Local host at first, self-hosted later.

Don't quite know anything about Ngin-X not about hosting in general, so I suppose this image being used for both is going to be fine (?) 😶
