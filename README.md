# Portfolio_JobSearch_Analytics
This project's goal is to serve as a showcase of my skills and knowledge in various aspects of the programing field as well as the technologies and tools being used in the industry. The project shall combine several small docker container modules to form a software.

# Tools:
Use tools such as git & github, docker, kubernetes (at a later stage) to better understand how to hone the tools while working on a project, and gain experience and in each of these tools.
 - Git & Github - manage the repository and utilize githubs built-in tools to manage the project's pacing, planning and progress.
   - Git  -
   - Git  -
   - Git  -
 - Docker - Separate each piece of code\script into a standalone atomic module. Each such module shall serve as a docker container.
 - Ngin-X\Tailscale - Reverse proxy for hosting.

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
- This container shall be written in either Node.JS or App Script. (To gain experience in Node.JS as another language in my arsenal)

# Container #2 - AI Integration:
- Data passed from Container#1 isn't structured. Each job offer\listing has its own description, details and format.
- This container shall use a LLama model I converted from the original meta weights, to convert extracted JSONs to objects based off-of defined parameters.
- Conversions shall happen using an mcp server (to gain some experience in mcp servers as well) to have the AI gather the data and use functions from an mcp servers to have the json built by code.
- The model can be instructed to write the json, however, since the model is outdated it might not perform as good as newer models. The model is preferred in this case, even if mundane, due to a smaller database it was trained on (potentially, less room for bias. We only need the model to perform actions and not handle back and furth conversations). Task successfully completing is much more likely using solid code rather than AI (better guarantees less errors, less room for AI-mess-ups as well as lessens the load on the context and cache).

- MCP server functions shall be written in C,(to gain better control and understanding of the C language).
- Functions shall write to json, save to json array, merge jsons. This shall server as practice for structs and memory management.
- The model shall run locally on a BC250 device, by routing traffic from and to it over the network.

# Container #3 - JSON to CSV:
- Transfer of the JSON array from Container #2
- C to convert the JSON to CSV and store in a DB
- Handle edge case use-cases (same workplace, but different submitter\listing, etc).
- Perform SQL\NOSQL CRUD operations (Practice SQL)
- This container is mainly for practice and a bit of dabbling in Database operation (as well as to make my life a bit of a living hell more than it is currently so I push myself a bit😁).

# Container #4 - Data Processing:
- Using python, fetch data from the Database.
- Data fetched shall then be processed using analytics libraries (pandas, mattplot, etc)
- Present basic data analysis for the listings (in which region are jobs searched for most, how many jobs are searched in total this month\day, how frequently does a workplace post listings, etc)
- A user shall have the option for filtering.

# Container #5 - Webpage frontend:
- Basic webpage presenting data processed in the previous container (#4).
- The webpage shall consist of basic HTML, CSS and JS.

# Container #6 - Webpage backend:
- Backend shall be written in Java Spring\Boot.

# Container #7 - Hosting:
- Docker image of Ngin X for running a self-hosted server (Local host at first, self-hosted later)
