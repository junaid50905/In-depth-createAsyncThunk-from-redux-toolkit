
#  In-depth createAsyncThunk from redux toolkit

## what is thunk?
Thunk is function that is returned from another function


## Examples

```javascript
//regular function
function thunkAdd(a){
    //thunk function
    return function(b){
        return a + b
    }
}
//calling regular function with 10 argument
const thunk = thunkAdd(10)

//calling thunk function with 5 argument
const result = thunk(5)

console.log(result)

```
#### Explanation: 
// In this example, thunkAdd function takes a as a parameter and returns a thunk function that takes b as a parameter. The thunk function return a + b.

//The thunk variable holds the invoke(call) thunkAdd function with 10 as argument.

// Then the result variable holds the thunk variable which means the thunk funciton. the thunk takes 5 as argument

//Now, console the output of result variable


