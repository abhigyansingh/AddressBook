## About
BE - node.js 
architecture - headless. ( headless, scalable, lean towards best practices .)

Here I've ruled out DENO as any advantages it provides will be nullified in r&d. 

### SOFTWARE REQUIREMENTS: 
Database: MySQL/ Mongo
Server: node.js,
Front end: HTML, xHTML, Java Script, React.js, Python (mayb :grin: ) 
Editor: VS code

### HARDWARE REQUIREMENTS: :scream: :confounded:
Processor: P4 should suffice
Ram : 512 MB RAM.
Storage : 30 GB 

## Steps to begin development on local system

### Step 1 :grin: Prerequisites 

To b installed in your local:-

- GIT - For Installing git follow [this article for better depth] (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) otherwise [this one]  (https://www.atlassian.com/git/tutorials/install-git)
- Python, anaconda, jupyter
- React-cli
- node.js -> install nodenv or nvm but not both. [install nvm ->easy to understand] (https://medium.com/@nbanzyme/easy-way-to-install-nvm-on-ubuntu-18-04-2cfb19ee5391) ,or [install nodeenv -> recomended] (https://github.com/ekalinin/nodeenv#nodejs-virtual-environment). Then install npm & node
- mysql
- mongodb
*contd

### Step 2: Cloning the repo & moving to development branch

**Take the repository url from**
- [repo_url] (https://github.com/abhigyansingh/tercio)
- at terminal or git bash enter `git clone <repo_url>`
- `cd` into project repository named tercio unless new name given
- Use `git status` to find the general stauts
- use `git checkout develop` to switch to develop branch
- To create & goto new branch '-b' can be used eg `git checkout -b hotfix2`
- Add files & commit

### Step 3: Verify all local installs, run the Project & work

**Node** - It often creates two instances on restrting the server, use ps -aux grep <pid> or something :persevere:
Start the dev server

### Step 4: Code, create PR after done, move related issue in board
 - Write code, git fetch, test/Unit test
 - Commit with msg (or no request merge)
  
