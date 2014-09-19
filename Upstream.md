##Explain what the "upstream" remote is usually used for

###What is Upstream and Downstream?

*Downstream* is where information flows from the repository to the user. You're downstream when you copy, clone, checkout (etc.) from a repository.

*Upstream* is where the original information comes from (i.e. the repository). 

###So, what is the "upstream" remote usually used for?

"Upstream" remotes are used when the user is working on a forked version of the origin. 

The user would identify the 'upstream' version using:

````
$ git remote add upstream [origin_git_url]
````


