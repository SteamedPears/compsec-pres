% Code Review Usability

Alexis Beingessner + Bheesham Persaud




# Programming is Hard

Usability doesn't matter if the system is insecure.

Any error can become a security vulnerability.





# Two Major Strategies for Verification

* Have a computer look at it
* Have a human look at it




# Computers

* Before merging: continuous integration (Travis, Jenkins)
* After merging: auditing tools (Coverity, AFL)



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



# Reviewing Code




