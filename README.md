# nao-utils

Utility behaviors useful for ADORE.

## Setting up the clock to disable warnings and LED signals

Log onto the robot, switch to root user and issue the command:

```
date MMDDhhmmYYYY.ss
```

Then restart Naoqi and wait for a few minutes, then reconnect. Sometimes, after the Naoqi restart, something goes wrong and it becomes impossible to reconnect to the robot. A hard reset is usually the only solution in such cases. It seems that it's safer to restart Naoqi through the web interface than through the command line.


