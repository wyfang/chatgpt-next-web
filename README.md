# NextChat

轻量的跨平台 AI 对话客户端，支持多家模型服务、Web 部署与桌面端。

[在线使用](https://chat.wangyifang.com/) · [上游文档](https://github.com/ChatGPTNextWeb/NextChat/blob/main/README_CN.md)

## 功能

- 支持 OpenAI、Azure OpenAI、Anthropic、Google 等模型接口
- 支持流式响应、Markdown、LaTeX、Mermaid、提示词模板与会话压缩
- 提供响应式 Web、PWA 与桌面端
- 浏览器本地保存会话数据

## 部署

最短本地启动：

```bash
yarn install
yarn dev
```

部署前至少配置所用模型服务的 API Key；访问密码、代理地址与各供应商参数见[上游环境变量文档](https://github.com/ChatGPTNextWeb/NextChat/blob/main/README_CN.md#环境变量)。不要把密钥提交到仓库或暴露在公开构建日志中。

## 版权说明

本项目是 [ChatGPTNextWeb/NextChat](https://github.com/ChatGPTNextWeb/NextChat) 的 Fork，依据 [MIT License](./LICENSE) 发布。上游版权归 NextChat；个人品牌和素材不在许可范围内。
