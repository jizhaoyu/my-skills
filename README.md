# My Claude Skills

这是一个 Claude Code 技能集合，包含四个实用的开发技能。

## 技能列表

### 1. Backend Design (`backend-design`)

Java 资深架构师技能，用于构建基于 Spring Boot 3.x + Spring Cloud 的企业级后端项目。

**特性：**
- 遵循 Alibaba Java Coding Guidelines 与 Google Java Style
- 支持 JDK 17/21、Maven/Gradle
- 支持 MyBatis-Plus 或 MyBatis-Flex
- 支持单体架构或微服务架构 (Spring Cloud Alibaba + Nacos)
- 完整的目录结构规范 (Domain Driven Layering)
- 统一响应格式、防御性编程、异常处理规范

**触发词：** `创建 Java 项目`、`新建 Spring Boot 项目`、`java-dev`、`生成后端架构`

---

### 2. Frontend Design (`frontend-design`)

创建独特、生产级的前端界面，具有高设计质量。

**特性：**
- 避免通用的"AI 风格"美学
- 支持 HTML/CSS/JS、React、Vue 等框架
- 注重排版、配色、动效和空间构图
- 创建令人难忘的视觉体验

**适用场景：** 网站、落地页、仪表盘、React 组件、HTML/CSS 布局等

---

### 3. Find Skills (`find-skills`)

帮助用户发现和安装 agent 技能的助手。

**特性：**
- 搜索开放的 agent skills 生态系统
- 使用 `npx skills` CLI 工具
- 支持按类别搜索：Web 开发、测试、DevOps、文档、代码质量等

**常用命令：**
```bash
npx skills find [query]    # 搜索技能
npx skills add <package>   # 安装技能
npx skills check           # 检查更新
npx skills update          # 更新所有技能
```

**浏览更多技能：** https://skills.sh/

---

### 4. React Best Practices (`react-best-practices`)

来自 Vercel Engineering 的 React 和 Next.js 性能优化指南。

**特性：**
- 包含 57 条规则，分为 8 个类别
- 按影响优先级排序

**规则类别：**

| 优先级 | 类别 | 影响 |
|--------|------|------|
| 1 | 消除瀑布流 (Waterfalls) | 关键 |
| 2 | Bundle 大小优化 | 关键 |
| 3 | 服务端性能 | 高 |
| 4 | 客户端数据获取 | 中高 |
| 5 | 重渲染优化 | 中 |
| 6 | 渲染性能 | 中 |
| 7 | JavaScript 性能 | 中低 |
| 8 | 高级模式 | 低 |

---

## 安装使用

这些技能文件位于 `~/.claude/skills/` 目录下，Claude Code 会自动加载并在适当的场景下使用它们。

## 许可证

各技能的许可证请参见各自目录下的 LICENSE 文件。
