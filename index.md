% Patch Review Usability

<center>Alexis Beingessner</center>
<center>Bheesham Persaud</center>


# Programming is Hard

Usability doesn't matter if the system is insecure.

Any error can become a security vulnerability.


# Two Major Strategies for Verification

* Have a computer look at it
* Have a human look at it


# Computers

* Before merging: continuous integration (Travis)
* After merging: program analysis (Coverity, AFL)


# Computers

* Good for catching common errors
* Good for preventing expected regressions
* Lacks semantic understanding of the domain


# Humans

* Before merging: patch review
* After merging: system audits


# Humans

* Can understand semantic issues
* Error-prone


# Patch Review

* First defense against errors
* Frequently performed
* Good interfaces important


# Diffs

Patches are usually presented as a *diff*

![diff.png](diff.png)

but diffs can be difficult to understand


# Better Diffs

One can emphasize parts that "really" changed:

![github-diff.png](github-diff.png)

Easier to understand => better review


# Heuristic Walkthrough of Patch Review

We performed a heuristic walkthrough of three different systems
for reviewing patches: Github, Bitbucket, and Reviewable.


# The Patches

Several real patches submitted to the Rust standard library's code base were selected, ranging from trivial to complex:

* A change that adds tests
* A small update
* A significant refactor


# Heuristics

ITSM Heuristics:

1. Visibility of activity status
1. History of actions and changes on artifacts
1. Flexiple representation of information
1. Rules and constraints
1. Planning and dividing work between users
1. Capturing, sharing, and discovery of knowledge
1. Verifcation of knowledge


# Task-Based Evaluation

First, several scenarios were considered:

* View the proposed change
* View updates to the proposed change
* View the current reviews of the change
* View the outstanding issues with the change
* View results from continuous-integration

For each type of patch and scenario, one expert reviewed and one submitted.


# Evaluation Criteria

After completing tasks with the heuristics in mind, we compare results.


Some low hanging fruit (URL toggle for whitespace, history sometimes not well
represented)

# Summary

* Programming is hard.
* Code reviews mitigate errors.
* Interfaces for code reviews are... &#128169;.
* We want to make things better.

