# laravel 问答理解

>   如何理解 Migrations and Eloquent ?
        
        Migrations是创建数据库结构及其版本控制，Eloquent是数据库模型，完全不相干

参考: [laracasts best answer](https://laracasts.com/discuss/channels/eloquent/what-i-understand-about-migrations-and-eloquent-in-laravel)

>   Eloquent Orm and Query Builder(查询构造器) 理解与区别 ?

        Orm是 对象关系映射，关系型数据库与业务实体之间的映射关系，通过该映射，只需
        简单操作对象的属性和方法即可，无须操作关联的复杂SQL语句.
        laravel中使用Eloquent Orm中的ActiveRecord模式，特点是模型与数据表一一对应.
        通过调用模型类相应方法实现对数据库的增删改查.

        Query Builder 依赖DB门面table方法，传入表明，再调用实例方法.

        两者关系:
        Eloquent本质上就是一个Query Builder,可以在Eloquent查询中使用 Query Builder所有方法
            
参考: 

[laracasts 回复下的内容，关注回答的Eloquent额外能做的](https://laracasts.com/discuss/channels/eloquent/what-i-understand-about-migrations-and-eloquent-in-laravel)

[Eloquent ORM 实例教程 —— ORM概述、模型定义及基本查询](http://laravelacademy.org/post/966.html)

[Laravel 数据库实例教程 —— 使用查询构建器对数据库进行增删改查](http://laravelacademy.org/post/908.html)