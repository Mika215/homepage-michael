# Dear Contributer

:+1::tada: First of all,thanks a loot for taking the time to contribute! :tada::+1:
Indeed it is an exciting thing to recive pull requests from some one determind like yours. 
Kindly, be in remind that by participating in this project, you agree to abide by the project owner's [CODE_OF_CONDUCT](https://github.com/Mika215/homepage-michael/blob/main/CODE_OF_CONDUCT.md).

The following is a set of guidelines for contributing to any of , [Michael T's](https://mika215.github.io/homepage-michael/) repositories on [GitHub](https://github.com/Mika215). 

These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

------------------------------------------------------------------------------------------------------

## Making Changes

* Create a topic branch from where you want to base your work.
  * This is usually the master branch.
  * Only target release branches if you are certain your fix must be on that
    branch.
  * To quickly create a topic branch based on master, run `git checkout -b
    fix/master/my_contribution master`. Please avoid working directly on the
    `master` branch.
* Make commits of logical and atomic units.
* Check for unnecessary whitespace with `git diff --check` before committing.
* Make sure your commit messages are in the proper format. If the commit
  addresses an issue filed in a given **project repository** start
  the first line of the commit with the issue number in parentheses.

  ```
      (mika-1234) Make the example in CONTRIBUTING imperative and concrete

      Without this patch applied the example commit message in the CONTRIBUTING
      document is not a concrete example. This is a problem because the
      contributor is left to imagine what the commit message should look like
      based on a description rather than an example. This patch fixes the
      problem by making the example concrete and imperative.

      The first line is a real-life imperative statement with a ticket number
      from our issue tracker. The body describes the behavior without the patch,
      why this is a problem, and how the patch fixes the problem when applied.
  ```
* Make sure you have added the necessary tests for your changes.


## Writing Translatable Code

Use clean and comonly used codes.

It is the responsibility of contributors and code reviewers to ensure that all
user-facing strings are marked in new PRs before merging.


## Submitting Changes

* Push your changes to a topic branch in your fork of the repository.
* Submit a pull request to the repository in the puppetlabs organization.
* After feedback has been given we expect responses within two weeks. After two
  weeks we may close the pull request if it isn't showing any activity.

## Revert Policy

By running tests in advance and by engaging with peer review for prospective
changes, your contributions have a high probability of becoming long lived
parts of the the project. After being merged, the code will run through a
series of testing pipelines on a large number of operating system
environments. These pipelines can reveal incompatibilities that are difficult
to detect in advance.

If the code change results in a test failure, we will make our best effort to
correct the error. If a fix cannot be determined and committed within 24 hours
of its discovery, the commit(s) responsible _may_ be reverted, at the
discretion of the committer and Puppet maintainers. This action would be taken
to help maintain passing states in our testing pipelines.

The original contributor will be notified of the revert in the Jira ticket
associated with the change. A reference to the test(s) and operating system(s)
that failed as a result of the code change will also be added to the Jira
ticket. This test(s) should be used to check future submissions of the code to
ensure the issue has been resolved.

### Summary

* Changes resulting in test pipeline failures will be reverted if they cannot
  be resolved within one business day.

### Further information 

* If you are looking for further information or some particular issues you can directly <a href="mailto:mikalsoyra@gmail.com">email</a>  the Project owner [Michael T](https://mika215.github.io/homepage-michael/) or reach him on [Slack](https://hackyourfuturebe.slack.com/team/U01JZFW9XNC)
