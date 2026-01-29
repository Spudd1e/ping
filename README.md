# Demo to understand repository dispatches

The 'ping' action in this repository fires a 'ping!' event targeted at the [pong repository](https://github.com/Spudd1e/pong.git)

On receiving the event, the pong repository triggers its workflow, outputting the payload, and replying with a 'pong!' event, which this repository listens for in the same way
