# ProjectStarterKit

Tutorial for getting started with an application.

Once you have an idea, it's time to make decisions about how to implement certain features.

For instance, storing data of any kind will require a database, and a database requires a host machine.  
A web server will require a host machine and software to accept socket connections, many pieces of software  
that can do this are relatively easy to set up and use (Apache, NGINX, Node.js Express).

In the context of a GitHub readme, this information should be below a `## Technologies` entry like this:

## Technologies

1. **Angular JS 1.X.X**

   If you're using Angular, document it as such.

2. **Node.js 4.2.6**
  * Express, body-parser

   Here's an example description for Node's Express:
   
   If Node is not already running the frontend won't be able to render anything.  
   This is because opening up a .html (in File Explorer) will not allow your browser to fetch any  
   scripts you include, because it needs to request that information over http  
   so you need something listening to http at 127.0.0.1 (localhost).

3. **Ubuntu Server 16.04 LTS (Prod. Env.)**

   Where is your application hosted?  
   If you are still developing locally, this might be appropriate:
   
   Currently we have nothing in production.

4. **PostgreSQL**

   The DBMS you choose, if you don't have it set up yet put this:
   
   Future scope.

5. **NGINX or Apache**

   Do you know what kind of software will be handling your web traffic?

## Development

###**Install Node.js (4.4.6 LTS):** https://nodejs.org/en/

###**Pull the repository:**

Install git, create a new folder, open terminal at that folder,  
run `git init` and then `git remote add origin https://github.com/Madison-SDC/site-sdc.git`  
then run `git pull origin master`. First you will need collaborator access to this repository,  
contact Ellery Kreloff for that.

###**Install dependencies:**

Since we are not including dependency sources files in the repository, you will need to retrive them using  
`npm install`. Once each, go in to the client and server directory and run `npm install`. **If you don't do  
that first this won't work!**

###**Run the server:**

Still inside the repository directory in your terminal, type  
`node server`. Now go to your browser and visit http://localhost:8080 and you will see the site!

