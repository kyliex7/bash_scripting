### create scripts that behaves like these:
### 1
```
    $ ./trap_basic
    script is running. press ctrl+c to send sigint or use 'kill <pid>' to send SIGTERM.
    # (in another terminal, send SIGTERM with: kill <pid> or press ctrl+c in this terminal)

    SIGTERM received, cleaning up resources.
    # or, if you pressed ctrl+c:
    SIGINT received, exiting gracefully.
```

### 2
```
    $ ./trap_custom
    script is waiting for custom signals SIGUSR1 or SIGUSR2.

    # (in another terminal)
    $ kill -10 <pid>  # sending SIGUSR1

    custom handler triggered!
```
