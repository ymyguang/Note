## Linux上手

### 文件权限

- 读[r]
- 写[w]
- 执行[x] execxte

命令：ll 

d rwx rwx rwx

- d -> 目录  文件类型
- 第一组：文件的所属用户
- 第二组：文件的所属组
- 第三组：其他用户



Linux同Windows一样，都有自己的文件结构，每个文件夹内都存有一类的内容

就像Windows中的Users文件存档是的用户的数据，windows文件内存储的是系统文件，program文件夹内存放的是安装的软件的文件，等等。类似有着的Linux同样的层级关系

- `boot`存放系统启动的相关文件

- bin：存放二进制可执行文件
- etc：存放系统配置文件
- home：存放用户文件
- root：超级用户目录
- opt：额外安装包
- usr：系统应用程序usr/local
- tmp：临时文件
- 