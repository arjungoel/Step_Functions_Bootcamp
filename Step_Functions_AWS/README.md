###### **STEP FUNCTIONS BOOTCAMP**


**STATES**:

States are elements in your state machine. A state is referred to by its name, which can be any string, but which must be unique within the scope of the entire state machine. States can perform a variety of functions in yourstate machine:

- Do some work in your state machine (a Task state)
- Make a choice between branches of execution (a Choice state)
- Stop an execution with a failure or success (a Fail or Succeed state)
- Simply pass its input to its output or inject some fixed data (a Pass state)
- Provide a delay for a certain amount of time or until a specified time/date (a Wait state)
- Begin parallel branches of execution (a Parallel state)
- Dynamically iterate steps (a Map state)


**PASS STATE**:

- A `Pass State` passes its input to its output, without performing work. Pass states are useful when constructing and debugging states machine.
- A `Pass State` is a way of building your function without worrying about the actual compute in the rules and it also lets you sort of manipulate the data.


- Individual states can make decisions based on their input, perform actions, and pass output to other states. In AWS Step Functions you define your workflows in the Amazon States Language (ASL).


Ques:- Can Step Functions be created with CloudFormation?
Ans:- It cannot be created via CloudFormation as the process is so fast though the Step Functions get created using API calls.


###### Color Code for Different Execution Status in Step Functions:

- `Cancelled Execution` -> Grey color
- `Failed Execution` -> Red color
- `Caught Error` -> Orange color
- `In Progress` -> Sky Blue color
- `Succeeded` -> Green Color


###### WorkFlows:

1. `Standard WorkFlows`: These can run up to a year.

2. `Express WorkFlows`: They are used for shorter invocations. They can run up to 5 minutes.


The State Machine must have atleast one terminal state, a state in which the end property is set to `true`.

To get suggestions while creating definitions for States Machine in VSCode use `CTRL + SPACE`

`AWSLambdaRole` is a built-in IAM role that allows you to invoke lambda functions.

The value of `StartAt` property must be the name of the existing state.

A `Task state` represents a single unit of work performed by a state machine.






###### LECTURE 2:

**AWS Step Functions Workflows for development and testing**:

- AWS Toolkit for Visual Studio Code
- Create a basic workflow
- Integrate that workflow into an AWS SAM app
- Setup CI/CD
- Iterate in AWS Lambda Functions
- Generating events with AWS SAM CLI


There is no direct support for AWS Step Functions inside SAM.







