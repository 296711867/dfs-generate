![dfs-generate](image/logo.png)
# dfs-generate
通过已有数据库表，生成FastAPI接口的工具项目,最终目的为FastAPI使用者，减少代码; 项目启发 Mybatis 逆向工程、[pdmaner](https://gitee.com/robergroup/pdmaner)

- d -> db 数据库
- f -> fastapi + uvicorn 接口服务
- s -> sqlmodel 数据实体、ORM模型
[桌面端下载](https://github.com/zy7y/dfs-generate/releases)


> 使用过程中有疑问、或其他宝贵意见 -> [issues](https://github.com/zy7y/dfs-generate/issues)，如果你对这个项目感兴趣，欢迎加入共同实现，
# 为什么不是其他
> 个人观点
1. 目前[Tortoise ORM](https://tortoise.github.io/)、 [Django Ninja](https://django-ninja.dev/)通过模型直接生成对应的Pydantic模型，均采用的 [动态创建模型](https://docs.pydantic.dev/latest/concepts/models/#dynamic-model-creation)，在Pycharm`.属性`无代码提示。
2. [SQLModel](https://github.com/tiangolo/sqlmodel/issues/654) 已有表生成模型，模型生成表，官方还未提供。
3. [fastapi-crudrouter](https://fastapi-crudrouter.awtkns.com/) 内部通过add_router方式注册路由，虽然代码减少了，但是灵活性变低了
4. 或该更多的使用表之间[逻辑关联](https://www.zhihu.com/question/20006142)

## Star History
<!-- STAR_HISTORY -->

[![Star History Chart](https://api.star-history.com/svg?repos=zy7y/dfs-generate&type=Date)](https://star-history.com/#zy7y/dfs-generate&Date)

<!-- /STAR_HISTORY -->
    



<!-- CONTRIBUTORS_SECTION -->
<!-- /CONTRIBUTORS_SECTION -->

