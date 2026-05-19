
## Question 1

### Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

1. Within a Github action that runs whenever code is pushed
2. Manually run them locally before pushing code
3. Run them all after all development is completed

I would place the automated tests inside a GitHub Action that runs whenever code is pushed to allow bugs and broken functionality to be detected automatically before ever merging or deploying code. It also helps maintain code quality throughout development instead of waiting until the end to test everything manually.

