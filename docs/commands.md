# 指令列表
?> 指令请以 `v.` 作为前缀 (中英句号均支持)  
    `[]` 表示可选参数, `<>` 表示必填参数

| 指令                       | 权限          | 描述                  |
| -------------------------- | ------------ | ---------------------- |  
| id                         | 无           | 获取用户/服务器 ID       | 
| setup `[分组名]` `[创建器名称]` `[临时频道名称]` `[默认人数限制]` `[声音质量]` | 管理员       | 设置一个语音频道 |
| name `<频道名称>`           | 无           | 设置所在语音频道的名称 |
| limit `<人数限制>`          | 无           | 设置所在语音频道的加入人数限制 |
| quality `<声音质量>`        | 无           | 设置所在语音频道的声音质量 (接受值: `1` `流畅` `2` `正常` `3` `高质量`) |
| kick `<@用户>`             | 无           | 踢出用户(多个以空格分割) |
