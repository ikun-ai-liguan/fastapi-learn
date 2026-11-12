# fastapi-learn

专业实习课堂作业：本地项目上传 Git（开源 / 闭源均可）。

## 项目简介

基于 Python + FastAPI 的最小 Web 示例项目，启动后访问根路径 `/`，返回一条 JSON 消息。

## 技术栈

- Python 3.13
- FastAPI
- Uvicorn（ASGI 服务器）

## 目录结构

```
fastapi-learn/
├── main.py        # FastAPI 应用入口
├── .gitignore     # Git 忽略规则
└── README.md      # 项目说明
```

## 本地运行

1. 安装依赖（缺啥装啥，默认全局安装；也可用 venv 虚拟环境做环境隔离）：

```bash
pip install fastapi uvicorn
```

2. 启动服务：

```bash
uvicorn main:app --reload
```

3. 浏览器或接口工具访问：

- 根接口：http://127.0.0.1:8000/
- 自动生成的接口文档：http://127.0.0.1:8000/docs

## 接口说明

| 方法 | 路径 | 说明 | 返回 |
| ---- | ---- | ---- | ---- |
| GET  | `/`  | 根接口 | `{"message": "Hello Shanghai"}` |

## Git 操作记录

```bash
git init                          # 初始化本地仓库
git add .                         # 暂存全部文件
git commit -m "init"              # 提交到本地仓库
git remote add origin <仓库地址>   # 关联远程仓库
git push -u origin main           # 推送到远程
```

## 作业登记表对应项

| 姓名 | git 仓库 | 项目 push | 数据库查看 |
| ---- | -------- | --------- | ---------- |
| （填写本人姓名） | （填写远程仓库地址） | 已 push | 本项目暂未涉及数据库 |
