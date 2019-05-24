# Windows10 提升生产力的技巧

## 系统快捷键

- win + A => 显示消息通知侧边栏
- win + B => 聚焦到右下角任务栏
- win + C => 召唤小娜
- win + D => 切换到桌面
- win + E => 打开资源管理器
- win + G => 打开游戏栏
- win + H => 执行语音命令
- win + I => 打开设置
- win + J =>
- win + K => 打开连接侧边栏
- win + L => 锁屏
- win + M => 最小化所有窗口
- win + N =>
- win + O =>
- win + P => 打开投影设置
- win + Q => 打开搜索
- win + R => 打开运行
- win + S => 打开搜索
- win + T => 聚焦底部任务栏
- win + U => 打开个性化设置
- win + V => 打开剪切板
- win + x => 打开快捷菜单
- win + Y =>
- win + Z =>
- win + + => 打开放大镜
- win + - => 缩小放大镜
- win + , => 预览桌面
- win + ; => 打开 emoji
- win + PrtSc => 全屏截图

## 命令行

- | 管道
  - dir | more
- <> 重定向
  - echo hello,world > foo.txt
- && 连接多个命令
  - mkdir test && cd test
- help \[cmd\] 显示帮助
  - help dir
- dir 列出当前文件夹的文件
  - dir /s
- type 显示文件内容
  - type foo.txt
- copy 复制文件
  - copy a.txt b.txt
- del 删除文件
  - del a.txt
- doskey 定制宏命令
  - doskey tp=cd c:
- more 对输出进行分页
  - dir | more
- ping 测试网络连通性
  - ping google.com
- pingpath 测试网络连通性并显示路由
  - pingpath google.com
- clip 访问剪切板
  - dir | clip

## PowerShell

- get-help 获取帮助
- new-item 新建文件
- get-content 查看文件内容
- set-content 向文件写入内容
- clear-content 删除文件内容
- copy-item 复制文件
- remove-item 删除文件
- get-childitem 显示当前文件夹内容
- get-alias 获取命令别名
- read-host 获取用户输入
- write-host 输出到命令行
- write-warning 写出警告
- invoke-item 用默认程序执行文件
- 特殊变量
  - \$\$ 上个命令的最后一个字符
  - $^ 上各命令的第一个字符
  - $_ 管道中的当前对象
  - $? 上个命令是否成功执行
  - $args 参数
  - $errors 错误数组
  - $HOME 家目录
  - $HOST 主机信息
  - $PID 进程信息
  - $TRUE 
  - $FALSE 
- enable-psremoting 接受远程ps命令
- logoff.exe 注销当前用户
- rundll32.exe user32.dll,LocKWorkStation 锁屏
- stop-computer 关机
- restart-computer 重启
- start-service 启动服务
- stop-service 关闭服务
- restart-service 重启服务
