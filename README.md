# Git and github how to!

Include guidelines for contributing to the project, explaining how to clone the repo, create a new branch, make changes, and submit a pull request. I used my own notes and school content as well as perplexity.ai to help make everything easy to read.
When contributing to a project communicate and mark clearly.

Table of Contents

- [How to Clone the Repository](#how-to-clone-the-repository)
- [How to Create a New Branch](#create-a-new-branch)
- [How to Make Changes](#make-changes)
- [How to Submit a Pull Request](#how-to-submit-a-pull-request)

---

## How to Clone the Repository:

1.  Have a repository you can take from online, for example, [this github repo](https://github.com/Felisong/githubexample)
2.  Make a folder of the exact same naming conventions in whatever file path you like to hold your projects.
3.  inside the file path , you should type

```
git clone https://github.com/Felisong/githubexample.git
```

4. Viola it is cloned! From here you can add commit and push any changes.

## Create a New Branch

There are two options, in your terminal you can type

1.

```
git checkout -b branchname
```

to make a branch and move the HEAD into it.

2.

```
git branch branchname
```

to make the branch and not move into it.

## Make Changes

You can make changes anytime, anywhere without being afraid of anything getting broken! We can work in branches specifically if you want to keep things contained in one area without affecting other areas as well.

But lets talk as if we're on the main branch making changes. Whenever your changes are finished and you're happy with them, you can then push it onto your github repository with....
First

```
git add filename
or
git add .
```

Second

```
git commit -m "whatever message you want to leave behind for other people looking at the code. Typically concise with whatever changes you made"
```

and lastly

```
git push
```

you should not have to specify the github since it is a clone, and it initialized with that cloning.

Sometimes, you want to upload only a branch, and not have all the information uploaded. In this case we specify.
you do the add and commit command I typed earlier and then....

```
git push origin branchname
```

Here we can lead into the last question

## How to Submit a Pull Request?

So since your branch is now up there, whoever is viewing your github and that commit you had pushed, they now have an easy button to press! There you can send a pull request to look over the code before merging it back onto the main branch.
