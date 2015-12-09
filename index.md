% Code Review Usability

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




# Better Diffs

Github emphasizes what actually changed:

![github-diff.png](github-diff.png)

Easier to understand => better review





