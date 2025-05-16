---
description: 了解梦之工具与如何安装使用
---

# MHDF-Tools 使用指南

## 🌟 插件特点
一款专为现代MC服务器打造的轻量化多功能工具，拥有这些贴心特性：
- 🪶 **轻盈体验**：仅保留核心功能，不占用额外资源
- 🌐 **智能跨服**：基于Redis的稳定跨服传输协议（成功率＞99.9%）
- 🏡 **全域家园**：支持多世界/跨服共享的家园系统
- 🛡 **数据安全**：MySQL/Redis双重数据保护

---

## 📦 环境要求
确保准备好这些运行环境：
```yaml
游戏版本: Minecraft 1.17+
运行环境: JDK 17+
服务端类型: Paper/Folia 及其衍生版本
```

---

## 🛠 安装指南

### 单服务器安装
1. [下载插件本体](https://github.com/MHDFCraft/MHDF-Tools/releases)  
   （选择 `MHDF-Tools-Bukkit` 版本）
2. 将插件文件放入服务端的 `plugins` 目录
3. 重启服务器完成加载

> 💡 小提示：首次启动后会自动生成配置文件哦！

### 群组服安装
1. **所有子服**执行单服安装步骤
2. 配置公共数据库：
   - MySQL（建议5.7+版本）
   - Redis（建议6.0+版本）
3. 根据群组端类型下载对应插件：
   - BungeeCord → `MHDF-Tools-Bungee`
   - Velocity → `MHDF-Tools-Velocity`
4. 将群组端插件放入对应 `plugins` 目录
5. 按顺序启动所有服务端

---

## ⚙️ 初始化配置
安装完成后需要这些基础配置：
1. 在 `config.yml` 中配置数据库连接
2. 通过 `/mhdf reload` 重载配置
3. 使用 `/mhdf version` 验证插件状态

