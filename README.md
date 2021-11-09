# Simple_py_logger
Simple, Colored, File and Line number printable python logger

I wanted to log like this
1. colored 
2. file name
3. line number
4. time
5. print type of logs by different func name

```
[2021-11-09 22:53:41.227][INF][test_logger.py:39] info log
[2021-11-09 22:53:41.229][DBG][test_logger.py:40] debug log
[2021-11-09 22:53:41.230][ERR][test_logger.py:41] error log
[2021-11-09 22:53:41.231][WRN][test_logger.py:42] warning log
[2021-11-09 22:53:41.233][CRC][test_logger.py:43] critical log
```

## How to use
```
from simple_py_logger import log

log.info('info log')
log.debug('debug log')
log.error('error log')
log.warning('warning log')
log.critical('critical log')
```

## features
- 0.2
  - At jupyter notebook there will be NO filename and line number
    ```
    [2021-11-09 23:01:34.591][WRN] warning log
    ```