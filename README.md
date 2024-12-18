<div align="center">

![new-api-horizon](https://github.com/Calcium-Ion/new-api/blob/main/web/public/logo.png)

# New API Horizon

特性版 - 基于New API开发的增强版本

<p align="center">
  <a href="https://github.com/Calcium-Ion/new-api/releases/latest">
    <img src="https://img.shields.io/github/v/release/Calcium-Ion/new-api-horizon?color=brightgreen&include_prereleases" alt="release">
  </a>
  <a href="https://hub.docker.com/r/CalciumIon/new-api-horizon/tags">
    <img src="https://img.shields.io/badge/docker-dockerHub-blue" alt="docker">
  </a>
</p>
</div>

</div>

## 关于New API Horizon

New API Horizon是基于开源项目[New API](https://github.com/Calcium-Ion/new-api)开发的特性版本。它保留了原版的核心功能,同时增加了一些新的特性和改进。这个版本不开源,但免费提供给用户使用。

## 获取方式

Docker镜像：calciumion/new-api-horizon:latest

## 新增特性

除了原版New API的所有功能外,New API Horizon新增以下特性

1. **[OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime/integration)** - 支持OpenAI的Realtime API，支持Azure渠道。
2. 支持`/v1/messages`接口（兼容OpenAI渠道转换为Claude格式）
3. 高性能，对部分场景专门优化，提高系统资源利用率，高并发下延迟显著降低

## WIP

1. [ ] 针对渠道的RPM限制
2. [x] 支持自定义令牌聊天选项
3. [x] 支持自定义充值选项
4. [x] 支持/v1/messages接口（兼容OpenAI渠道转换）
5. [x] 性能优化（WIP）
