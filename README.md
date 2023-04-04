# SomeApp

## How to automatically add a checklist to a pull request. 
1. Add a file called `PULL_REQUEST_TEMPLATE.md` in the root folder of the repository. [See this link for more details](https://github.blog/2016-02-17-issue-and-pull-request-templates/)
2. Add a check list in markdown format 
eg: 
```
Have I done these ?:
- [ ] Ran Prepare
- [ ] Tested as roles
- [ ] Added unit tests
- [ ] Added regression test areas to the card.
- [ ] Showcase done.
```
 3. Create a PR. 
 4. The check list will appear at the rop of the `Conversation` tab of the PR. 
 ![foo](./images/how%20checklist%20looks%20in%20github%20pr.png)