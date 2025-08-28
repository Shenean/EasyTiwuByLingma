# 题库系统

## 简介
本项目是一个基于 **前后端分离** 的题库系统，支持题库上传、管理、练习记录等功能。前端基于 Vue + Naive UI，后端采用 Spring Boot 微服务架构，数据持久化到 MySQL。

---

## 技术栈

### 前端
- **Node.js 22**  
- **Vue 3**  
- **Vite**  
- **Naive UI**  
- **Pinia / Vue Router**

### 后端
- **JDK 17**  
- **Spring Boot 3**  
- **Spring Cloud Alibaba**（微服务支持）  
- **Spring Security + OAuth2 + JWT**（认证鉴权）  
- **MyBatis-Plus**（ORM 框架）  
- **Redis**（缓存与会话管理）  

### 数据库
- **MySQL 8.0**

### 构建与工具
- **Maven 3.9.9**（依赖管理与构建）  
- **Docker / Docker Compose**（容器化部署，支持 Nacos + MySQL + Redis）

---

## 环境要求

- Node.js `>=22`
- JDK `>=17`
- Maven `>=3.9.9`
- MySQL `>=8.0`
- Redis `>=6.0`

---

## 快速开始

### 前端
```bash
cd frontend
npm install
npm run dev
