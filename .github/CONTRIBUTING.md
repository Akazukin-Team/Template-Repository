# Akazukin-Team Contributors Guide

Below is our guidance for how to report issues, propose new features, and submit contributions via Pull Requests (PRs).


## Chapter

 * [Report issues](#report-issues)
 * [Suggest features](#suggest-features)
 * [Developments](#developments)




## Report issues

**If the issue matches [Security Vulnerability](./SECURITY.md#definition-of-a-security-vulnerability), you follow [the Reporting a Vulnerability](./SECURITY.md#reporting-a-vulnerability).**

If you find a bug, first, check there are no issue (including closed issues) that is similar or duplicate, and pull requests adressing it.

Second, you create a issue and fill form as much as possible.
These information will help us patch the issue much quicker.

And then, please check the issue regularly.
We may ask some questions to patch the issue.




## Suggest features

If you want to suggest a feature, first, check there are no features (including closed features) that is similar or duplicate, and pull requests adressing it.

Second, you create a issue and fill form as much as possible.
These information will help us make the feature much quicker and easier.

And then, please check the suggestion regularly.
We may ask some questions to make the feature.




## Developments

### Getting Started

First, you will cloning the repository and checkout branch to your development branch.

Generally, It is not allowed to changes at main/master branch.
We follow the rule, so if you were do that, we will dismiss PR.


Second, modify only the minimum.

If you have many changes in PR, it may conflict other PRs.


Third, check style and test code.
**IT IS IMPORTANT!**

The code requirements are written in [Code Requirements](#code-requirements),
so please check there.


Finally, push the changes and create PR.

Your PR will be merged if you have followed Code Requirements, etc.
It may take a while to get your PR merged, but it will happen.
Please check it from time to time.
It may take a while. Pray to God and wait.



### Code Requirements

 * Without any exceptions thrown
 * Optimized code
 * Without commenting out code
 * Created the test module for changed code
 * Passed checkstyle "Sun Checks"
 * Use final as much as possible
 * Processing speed is as fast as possible
 * Low processing costs



### Comment of Commit

 * Be as concise as possible
 * Write what you changed from what to what
 * Write in English only
 