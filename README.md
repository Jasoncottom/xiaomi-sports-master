# # 小米运动修改刷步数

> 小米运动修改步数

### 设置账号密码

添加名为 **USER**、**PWD**、**STEP** 的变量，值分别为 **账号（手机号）**、**密码**、**步数**

### 多账户

用 **#** 分割 分别保存至 变量 **USER** 和 **PWD**

#### 例如

**123#124** 变量 **USER**

**abc#abd** 变量 **PWD**

### 自定义启动时间

编辑 **sched.add_job(mains, 'cron', hour='7', minute='32')**

hour 为小时 minute 分钟

### 启动

双击运行即可

## 注意事项

多账户的数量和密码请一定要对上 不然无法使用!!!
