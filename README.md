# github-action

# Hello alien javascript action

This action prints "Hello alien" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"alien"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-alien-javascript-action@v1.1
with:
who-to-greet: 'Mona the Octocat'
