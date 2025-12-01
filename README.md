# Luminahub

Luminahub 是一个知识获取与分享社区项目，当前以单仓库形式组织前后端代码。

## 项目结构

```text
luminahub/
  backend/   Spring Boot 后端
  frontend/  React + Vite 前端
```

## 技术栈

- 后端：Java 21、Spring Boot、Spring Security、Spring AI、MyBatis、MySQL、Redis、Kafka、Caffeine、Canal、Elasticsearch、阿里云 OSS
- 前端：React、TypeScript、Vite

## 本地开发

### 启动前端

```bash
cd frontend
npm install
npm run dev
```

### 启动后端

```bash
cd backend
mvn spring-boot:run
```

## 说明

- `backend/README.md` 包含后端相关文档和设计说明。
- `frontend/README.md` 包含前端构建与运行说明。
