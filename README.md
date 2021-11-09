# devfacPyLog
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

![sample_output](https://github.com/transpine/simple_py_logger/blob/main/sample_output.png?raw=true)

## How to use

```
from devfacPyLogger import log

log.info('info log')
log.debug('debug log')
log.error('error log')
log.warning('warning log')
log.critical('critical log')
```

## features
- At jupyter notebook there will be NO filename and line number(0.1)
    ```
    [2021-11-09 23:01:34.591][WRN] warning log
    ```
