TimeBlock
=========

TimeBlock is composed by a couple of macros:

* traceElapsedTimeInBlock: A simple little helper to measure the time spent for executing a block.
* traceSlowExecutionBlock: Similar to the first one but just log if the block takes more than a indicated amount of seconds.


## Usage

```
traceElapsedTimeInBlock (@"Log message", ^{
  // Write here the code you want to measure
});
```

```
traceSlowExecutionBlock (@"Log message, 25, ^{
  // Write here the code you want to log if it takes more than 25 seconds on runtime
});
```
