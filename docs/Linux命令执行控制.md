## Linux命令执行控制&&与|| ##
> &&：表示前一条命令执行成功后才执行后一条命令  
> ||：表示前一条命令执行失败后才执行后一条命令
1. &&
    **语法：**  command1 && command2
    ```Linux
    $touch file.out
    $echo 'test123' > file.out
    $cat file.out && echo 123
    $cat nofile && echo 123
    ```
2. ||
    **语法：**  command1 || command2
    ```Linux
    $cat file.out || echo 123
    $cat nofile || echo 123
    ```
