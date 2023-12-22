# algorithmic_trading

This is a private repository. 

This project aims to explore stock price prediction opportunities caused by a stock's volatility when earnings calls are released. Long-term-short-term (LSTM) models can be very powerful for time-series related predictions, and large-language models (LLMs) can be powerful for leveraging complex patterns within data. Our goal is to see if either of these models (or a combination of the two) can provide reasonable predicitons for a stock's price once earning calls are made public. 

Git basics for beginners / anyone who forgot:

Use git branches to create your own copy of the code base that is aimed at a specific objective. This helps with version control and helps isolate code changes while mitigating merge conflicts. It is poor practice to write code directly in the main branch of a repository. To create a branch, use the following command. 
```git checkout -b <branch_name>```

To switch between branches, use the following command: 
```git checkout <branch_name>```

To see your current branch, you can use either of the following commands:
```git branch``` or ```git status```

To push changes to the remote repository, use the following workflow:
1. ```git add <file_name>``` This will stage your local changes for the specified file to your branch so that you can commit it.
3. ```git commit -m <message>``` This will commit all of your staged changes to your branch. Always add a descriptive message about the changes you made so other can understand what you did and why.
4. ```git push``` This will add your changes to the main branch in the remote repository (by default). This means that others will be able to pull and acquire your changes by using the ```git pull``` command.

To obtain changes that other have pushed, use the following command:
- ```git pull``` This will update your branch with any updates from the main branch on the remote repository. Note that you should pull regularly and not only when pushing code.


A helpful image to visualize common Git workflows:


<img width="617" alt="image" src="https://github.com/et-racer2/algorithmic_trading/assets/97319300/421d5f29-d6d7-4f2f-98fe-bb2d16468adb">



Note: If two people try to push changes to the same file, then a merge conflict may occur. This is fine, but be careful. Luckily, Git also allows you to rollback to any past version of a branch if you make a mistake or need to go back for any other reason. 
