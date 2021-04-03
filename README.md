# hello-world-javascript-action
Github Action for printing "Hello World" or "Hello" + the name of a person to greet on the log.

## Inputs

### `who-to-greet`
**Required** The name of the person to greet. **Default**=`"World"`.

## Outputs

### `time`

The time we greeted you at.

## Example usage

    uses: actions/hello-world-javascript-action@v1
    with:
      who-to-greet: 'Mona the Octocat'
