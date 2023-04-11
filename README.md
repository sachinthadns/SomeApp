# SomeApp



## How to automatically add a checklist to a pull request. 
1. Add a file called `PULL_REQUEST_TEMPLATE.md` in the root folder of the repository. [See this link for more details](https://github.blog/2016-02-17-issue-and-pull-request-templates/)
2. Add a check list in markdown format 


eg: 
```
# Code Readiness Checklist 

This checklist is to be completed by the pull request creator.
Reviewer will not review the code until all items are ticked.
The purpose of this checklist is to remind the developer of frequently missed steps when writing code. 

## Have I done these? 
*Please tick items if you have done them OR they are not applicable for this code change*
- [ ] Ran Prepare
- [ ] Tested as roles
- [ ] Added unit tests
- [ ] Added regression test areas to the card
- [ ] Showcase done
```

 3. Create a PR. 
 4. The check list will appear at the rop of the `Conversation` tab of the PR. 
 ![foo](./images/how%20checklist%20looks%20in%20github%20pr.png)
 5. Author of the PR would be able to tick the check boxes. 
 
 # Code Readiness checklist. 

This check list is to be completed by the pull request creator.
Reviewer will not review the code until all items are checked.
The purpose of this checklist to remind the developer of the often missed steps when writing code. 

Have I done these? 
(Please tick items if you have done them OR they are not applicable for this code change)