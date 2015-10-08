Paycoin.com
===========

Official repository for https://www.paycoin.com

What is Paycoin?
----------------

Paycoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Paycoin uses a proof-of-stake method in order for
the Paycoin blockchain network to achieve distributed consensus. Paycoin Core is
the name of open source software which enables the use of this currency.

The repository for Paycoin Core can be found here: https://github.com/PaycoinFoundation/paycoin

Contributing
------------
Paycoin.com is a community driven project and accepts contributions of code from the community.

Working With GitHub
-------------------

GitHub allows you to make changes to a project using git, and later submit them in a "pull request" so they can be reviewed and discussed. Many online how-tos exist so you can learn git, [here's a good one](https://www.atlassian.com/git/tutorial/git-basics).

In order to use GitHub, you need to [sign up](http://github.com/signup) and [set up git](https://help.github.com/articles/set-up-git). You will also need to click the **Fork** button on the paycoin.com [GitHub page](https://github.com/PaycoinFoundation/paycoin.com) and clone your GitHub repository into a local directory with the following command lines:

```
git clone (url provided by GitHub on your fork's page) paycoin.com
cd paycoin.com
git remote add upstream https://github.com/PaycoinFoundation/paycoin.com.git
```

**How to send a pull request**

1. Checkout to your master branch. `git checkout master`
2. Create a new branch from the master branch. `git checkout -b (any name)`
3. Edit files and preview the result.
4. Track changes in files. `git add -A`
5. Commit your changes. `git commit -m '(short description for your change)'`
6. Push your branch on your GitHub repository. `git push origin (name of your branch)`
7. Click on your branch on GitHub and click the **Compare / pull request** button to send a pull request.

When submitting a pull request, please take required time to discuss your changes and adapt your work. It is generally a good practice to split unrelated changes into separate branches and pull requests.

**How to make additional changes in a pull request**

You simply need to push additional commits on the appropriate branch of your GitHub repository. That's basically the same steps as above, except you don't need to re-create the branch and the pull request.

**How to reset and update your master branch with latest upstream changes**

1. Fetch upstream changes. `git fetch upstream`
2. Checkout to your master branch. `git checkout master`
3. Replace your master branch by the upstream master branch. `git reset --hard upstream/master`
4. Replace your master branch on GitHub. `git push origin master -f`

Production
----------
This repository is pulled to production every Monday.
