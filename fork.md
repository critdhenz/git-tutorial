
See [Using pull
requests](https://www.atlassian.com/git/tutorials/making-a-pull-request).

#### 1. Fork Donal's repo on GitHub

Use the Bitbucket interface to fork
https://bitbucket.org/cynder/git-tutorial to your
GitHub account.

#### 2. Clone your new repo to your computer

From the command line:
```
git clone git@bitbucket.org:<your_bitbucket_username>/git-tutorial.git
```

Now you have a working copy of the repository.

*Donal says*: I always use the `git@` (= `git://` over SSH) protocol for any
repo I own. I find it easier to set up an SSH key than manage
username/password. It's faster and less flakier than the `https://` protocol.

By the way, never use the `git://` protocol by itself. It doesn't have
authentication.
