### 自动构建Velocity.jar指南

1：fork本项目

2：在Actions菜单允许 `I understand my workflows, go ahead and enable them` 按钮

3：在`proxy/src/main/java/com/velocitypowered/proxy/Velocity.java`文件里 149到165 中添加需要的环境变量，不需要的留空，保存后Actions会自动构建

4：等待3分钟左右，在右侧的Release里下载velocity.jar文件
