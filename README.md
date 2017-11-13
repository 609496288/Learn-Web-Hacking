# Learn Web Hacking

Web相关的知识很杂、很多，很多时候想查但是很不方便，所以用rst把相关的知识简单整理在这。另外也是对自己的一个积累。

其中会引用一些其他blog，在文末皆标出相应链接。

未上传build后的文件，若有需要安装sphinx后运行make命令即可

#### 目录结构

- 基础知识
    - 基础概念
    - 审计技巧
    - 测试技巧
    - 相关工具
- 漏洞介绍
    - 命令注入
    - 配置不当
    - CSRF
    - 文件读取/上传/包含
    - 逻辑漏洞
    - RCE
    - SQL注入
    - SSRF
    - XSS
    - XXE
- 语言相关
    - PHP
    - Python
- 其他
    - 缓存欺骗

### Generate HTML

```shell
pip install sphinx
make html
```