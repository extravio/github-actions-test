# github-actions-test
Test using the github actions/toolkit

```
docker run -it --rm -v /home/mikael/dev/github-actions:/home/node/app --name github-actions node:18
```

# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'