# /cmd/pty

列出当前正在执行的命令列表

## 参数

1. `id`: 机器ID
2. `pid`: 进程ID

## 返回值

    http_code=200
    body=内容

## channel不存在

    http_code=404
    body=channel not found

## 错误，其他异常

    http_code=500
    body=错误内容