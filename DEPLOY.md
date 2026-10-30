# 发布日报测试站

仓库 Settings → Pages → Build and deployment：选择 Deploy from a branch，分支 main，目录 / (root)，保存。站点地址以 Pages 设置页实际返回为准。

index.html 从同目录 reports.json 读取归档数组。更新日报时按 date 替换或追加，保留其他日期，提交 main 后自动发布。页面不依赖原站数据接口，没有第三方字体或脚本，不含建议动作和统计模块。

公开仓库不得提交密码、访问令牌或内部资料。
