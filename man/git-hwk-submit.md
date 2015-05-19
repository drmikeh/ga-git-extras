git-hwk-submit(1) -- Submit Homework via GitHub
=================================================

## SYNOPSIS

`git-hwk-submit` [-n, --netrc, -d, --debug]

## DESCRIPTION

  Verifies a local Git branch and pushes it to GitHub, then creates a Pull Request.

## OPTIONS

  -n, --netrc

  Use the local .netrc file for authentication with GitHub.

## EXAMPLES

  * Submitting a homework assignment

    $ git hwk-submit

    ```
    Verifying...
    hwk-00-test-2
      You are on a homework branch - Good Job!
      I hope you remembered to commit your work!

    Now lets push this branch...
    Everything up-to-date

    Preparing pull-request for drmikeh/WDI_ATL_3 - 'hwk-00-test-2'

      Enter a title for the PR: My Solution
      Enter a message body for the PR: I had a little trouble with the for loops.

    About to create pull-request
    Are you sure? [y/N] y

    Your pull-request has been created.
    You can see your pull-request at:   "https://github.com/drmikeh/WDI_ATL_3/pull/21"
    ```

## AUTHOR

Written by Mike Hopper &lt;<drmikeh@gmail.com>&gt;

## REPORTING BUGS

&lt;<https://github.com/drmikeh/ga-git-extras/issues>&gt;

## SEE ALSO

&lt;<https://github.com/drmikeh/ga-git-extras>&gt;