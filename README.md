# 实验室网站管理（CAMALAB@HDU）

> CAMA-LAB网站：http://camalab.hdu.edu.cn/

## 网站管理 

### 1.1 Git同步

该网站源文件在 http://coding.net/ 上，使用Git进行同步管理。

### 1.2 FTP托管

实验室网站托管在学校服务器上，使用FTP管理。可以使用FileZilla等软件。

> 注意：ftp只有校内可以上传。

### 1.3 日常管理

更新网站的步骤：

> 1. 从Git同步最新的网站文件 ``git pull``
>
> 2. 在本地进行修改
>
> 3. 将更新后的文件同步到Git上：
>
>    3.1 填写变更介绍（简要说明做了哪些更改）：
>
>    - 如果有修改的文件：``git commit -am "变更介绍"``
>    - 如有增加新的文件，则使用：``git add .`` & ``git commit -m "变更介绍"``
>
>
>    3.2 将文件推送到Git：``git push origin``
>
> 4. 登录FTP，将修改后的文件上传到FTP服务器端，覆盖原有文件
