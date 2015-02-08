This is just an example of how to make a non blocking UI which uses events and a state machine. This is much better than having the UI
lock up all the time. This is a standard architecture.

I got all of this from here "https://www.youtube.com/watch?v=RuIN31rSO2k"

This wont work on a real time target like a MyRIO as they don't support events
instead refer to LabVIEW realtime 2 course and use a message queue type architecture using shared variables