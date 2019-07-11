# Lambda API
Returns the first word that occur more than once in a query string.

## Link
`https://9bzxzxha12.execute-api.us-east-2.amazonaws.com/repeatedWord`
* Example usage: `https://9bzxzxha12.execute-api.us-east-2.amazonaws.com/repeatedWord?string=This is a test`

## Test
[Tests using API gateway](./testImages)

## Deployment issues
* Error parsing JSON when doing test - don't use json, instead, put the string i..e "This is sample"
* Add build dependencies:
```
apply plugin: 'java'
sourceCompatibility = 1.8
targetCompatibility = 1.8

```
