This is an example file for a contribution guide. It suggests using a DCO.

# Contribution guide
This guide will assist you in order to sucessfully submit contributions for the this project.  

## Obtain the current version of the source code
Assure that you are working with the latest stable version.

## Describe your changes
Absolutely describe your changes regardless of what problem you solved nor how complex your changes are. Keep the following points in mind:

### General
* What is your motivation to do to this change?
* Why it is worth fixing?
* How will it affect end-user?
* If optimisations were done - quantify them. Present trade-offs (e.g. run-time vs. memory).
* Evaluate your contribution objectively. What are pro's, con's?
* One contribution should solve only one problem. If not split it.
* Your description should be self-explanatory (avoiding external resources).

### Linking, referencing & documentation
* If you link to tickets/mailing lists etc. reference to them. Summarise what is its principal outcome.
* When referencing specific commits: state the commit ID (use the long hash) + (!) the commit massage in order to make it more readable for the reviewer.

### Implementation specific
* How you solved the problem?
* If your solution is complex: provide an introduction before going into details. 
* If your patch your solution describe what you have done and why.


## Test and review your code
Test it on a clean environment.

Review your code with regards to our [coding guidelines](#coding-guidelines).


## Check and act on the review process
You may receive comments regarding your submission. In order to be considered you must respond to those comments. 


## Sign your work
You must sign the [Developer Certificate of Origin (DCO)](https://developercertificate.org/) for any submission. We use this to keep track of who contributed what. Additionally you certify that the contribution is your own work or you have the right to pass it on as an open-source patch.

**To do so you read the DCO and agree by adding a "sign-off" line at the end of the explanation of the patch like in the example below:**

```text
Signed-off-by: Joe Contrib <joe.contrib@somedomain.com>
```

Fill in your full name (no pseudonyms) and your email address surrounded by angle brackets.

Small or formal changes can be done in square bracket notation:

```
Signed-off-by: Joe Contrib <joe.contrib@somedomain.com>
[alice.maintain@somedomain.com: struct foo moved from foo.c to foo.h]
Signed-off-by: Alice Maintain <alice.maintain@somedomain.com>
```

## Do the pull request

```git
git request-pull master git://repo-url.git my-signed-tag
```

See also [here](https://help.github.com/en/articles/requesting-a-pull-request-review) for more information about pull requests in general on GitHub.


----------------------------------------------------------------
# Coding guidelines
Write some general lines about your guidelines. For example if it is based on something.

## Style
* Naming conventions
* British English shall be used in function names and comments
* `TODO`, `FIXME` and similar tags should be in the format: `# TODO: This is my TODO (<author>)`
    * First letter in the comment is a majuscule
    * The comment ends with the name of the author or with an unique and consistent abbreviation/alias/username/pseudonym (preferably your initials if still available; if you are unsure check the [CONTRIBUTORS](../CONTRIBUTORS) file)
* Etc.
    
## Exceptions

More sections could follow.

----------------------------------------------------------------

Add further important topics below.
