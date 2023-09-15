# Async Await Notes

The brower is ALWAYS running an event loop to check code. at first it will call synchronous functions, then on the second time around it will call the async functions. 

You are basically telling the computer that it can post the synchornous right now but wait on the async as it gets data from an API or your API, then when it is gotten, it can post the data. 