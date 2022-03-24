# quickStart-GithubActions-test-2

❯ gh repo create quickStart-GithubActions-test-2 --public

❯ echo "# quickStart-GithubActions-test-2" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/Misk77/quickStart-GithubActions-test-2.git  
git push -u origin main  


❯ mkdir -p .github/workflows && $_  
❯ vim demo.yaml  

Now we define the workflow:  

<pre>  
name:  
triggger on event  
jobs:  
  nameOfJob  
    Which env to run inside  
    steps, actions to do  
 </pre> 

run = command inside the environment  
uses = use a actions (module).   

❯ git add .  
❯ git commit -m "start github action"  

❯ git push  


# Check the runners and jobs from the terminal. 

> ❯ gh run list   
For details on a run, try: gh run view <run-id>    
  
gh run view 1825414865    

For more information about the job, try: 
> gh run view --job=5145631115  
 


TEST PROTECTIONS 
asdasdasdasdasdasddsfsdsds
