# Promises

**_Promises_** are used to handle asynchronous operations in JavaScript. <br>
**_Promises_** are the ideal choice for handling multiple callbacks at the same time, thus avoiding the undesired callback hell situation.<br>

## Benefits of Promises <br>

- Improves Code Readability
- Better handling of asynchronous operations
- Better flow of control definition in asynchronous logic
- Better Error Handling

A **_Promise_** has four states:

- **_fulfilled_** : Action related to the promise succeeded
- **_rejected_** : Action related to the promise failed
- **_pending_** : Promise is still pending i.e. not fulfilled or rejected yet
- **_settled_** : Promise has fulfilled or rejected

A promise can be created using Promise constructor.<br>
**_Syntax_** <br>
_var promise = new Promise(function(resolve, reject){<br>
//do something<br>
});_

## Parameters

Promise constructor takes only one argument which is a callback function (and that callback function is also referred as anonymous function too). <br>
Callback function takes two arguments, **_resolve_** and **_reject_** <br>
Perform operations inside the callback function and if everything went well then call **_resolve_**.
If desired operations do not go well then call **_reject_**.

## Promise Consumers <br>

Promises can be consumed by registering functions using **_.then_** and **_.catch_** methods.

- **_then( )_**<br>
  **_then( )_** is invoked when a promise is either resolved or rejected. It may also be defined as a career which takes data from promise and further executes it successfully.
