A `Pass State` passes its input to its output, without performing work. Pass states are useful when constructing and debugging states machine.

Ques:- Can Step Functions be created with CloudFormation?
Ans:- It cannot be created via CloudFormation as the process is so fast though the Step Functions get created using API calls.

--------------------------------------------------------------
Color Code for Different Execution Status in Step Functions:
--------------------------------------------------------------

`Cancelled Execution` -> Grey color
`Failed Execution` -> Red color
`Caught Error` -> Orange color
`In Progress` -> Sky Blue color
`Succeeded` -> Green Color

-------------
WorkFlows:
-------------

1. `Standard WorkFlows`: These can run up to a year.

2. `Express WorkFlows`: They are used for shorter invocations. They can run up to 5 minutes.


The State Machine must have atleast one terminal state, a state in which the end property is set to `true`.

To get suggestions while creating definitions for States Machine in VSCode use `CTRL + SPACE`

`AWSLambdaRole` is a built-in IAM role that allows you to invoke lambda functions.

The value of `StartAt` property must be the name of the existing state.

A `Task state` represents a single unit of work performed by a state machine.
