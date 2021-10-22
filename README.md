# atlassian-forge-test
Atlassian Forge test apps

I want to avoid installing forge cli globally, so I install it as a dev dependency in the parent folder of all projects:

    npm install @forge/cli --save-dev

and then use for example:

    npx forge create 
    
instead of just:

    forge create
    
on the command line.
