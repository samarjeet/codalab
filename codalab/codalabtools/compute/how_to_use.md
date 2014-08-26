## CodaLab Compute Service

### Useful commands

```
python service.py install
python service.py start
python service.py stop
python service.py remove
```

### Get status

```
sc query CodaLabCompute
```

Outputs

```

SERVICE_NAME: CodaLabCompute
        TYPE              : 10  WIN32_OWN_PROCESS
        STATE              : 4  RUNNING
                                (STOPPABLE, NOT_PAUSABLE, IGNORES_SHUTDOWN)
        WIN32_EXIT_CODE    : 0  (0x0)
        SERVICE_EXIT_CODE  : 0  (0x0)
        CHECKPOINT        : 0x0
        WAIT_HINT          : 0x0
        
```        
