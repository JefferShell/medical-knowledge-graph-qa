## Stock Knowledge Graph System

**README.md**

## 项目简介

本系统是针对股票数据知识图谱的应用，可以快速找到股票企业相关问题答案。

**重要提示：**

- 该项目使用 neo4j 作为底层图数据库，建议对 neo4j 有基本的了解。
- 数据量较大，第一次使用时请确保有足够的内存和计算资源。


## 主要功能

- 基于知识图谱展示股票相关信息。
- 支持通过三元组方式查询股票相关问题。
- 提供股票问题与答案问答功能。


## 技术架构

- 前端：HTML、CSS、JS
- 后端：Django
- 图谱展示：eCharts
- 数据库：Neo4j（图谱数据）、SQLite（关系型数据）


## 使用说明

1. 克隆项目：
```
git clone https://github.com/your-username/your-repo.git
```

2. 安装依赖项：
```
pip install -r requirements.txt
```

3. 初始化数据库：
- 启动 neo4j 服务。
- 执行 `python manage.py migrate` 以初始化 SQLite 数据库或 `neo4j-import.py` 以初始化 neo4j 数据库。

4. 运行项目：
```
python manage.py runserver
```

## 联系方式

微信号：zt745324325