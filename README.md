# Hello world docker action123

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.
https://github.com/paygoc6/action-pull-request-another-repo
https://github.com/marketplace/actions/push-directory-to-another-repository

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
