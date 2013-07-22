The [Programming Best Practices
Tidbits](https://github.com/thomasdavis/best-practices) has a lot of fantastic
guidelines for writing code that are mostly language agnostic.

# General

- From Piper [aaronmerriam]:
    - It it is not in source control, it does not exist.
        - To work collaboratively with others you must use version control.
          See
          [the](http://www.troyhunt.com/2010/11/you-deploying-it-wrong-teamcity.html)
          [following](http://www.troyhunt.com/2011/05/10-commandments-of-good-source-control.html)
          [reasons](http://www.makeuseof.com/tag/git-version-control-youre-developer/).
    - It must be tested.
        - If the code you write is not tested, there is no reasonable way to
          collaborate without knowing whether what you are doing has broken
          something, or whether or not it worked at all in the first place.
        - I suggest using [Travis CI](https://travis-ci.org/).  You can see
          this in practice in the [ladder](https://github.com/Apogaea/ladder)
          application.
    - Write maintainable code.
        - Your code should have useful comments and documentation.
        - Don't be clever.  If you are writing the *cleverest* code you can,
          you won't be able do debug it later.
    - Use an editor that shows you syntax errors.
    - Make [good commits](http://www.abisource.com/wiki/Good_Commit_Message_Guidelines).
    - Use pull requests
        - Pull requests are a great way to organize your code and let others
          know what you are working on.


# Python

- Adhere to [pep8](http://www.python.org/dev/peps/pep-0008/)
- [The zen of python](http://www.python.org/dev/peps/pep-0020/).

# JavaScript

- Use a framework.

# PHP


