### watch
[watch](https://blog.csdn.net/qq_42786011/article/details/92802714)

```
watch的数据不能在本页面改，不然会报错。去掉deep不然

```
### router
```
@click="jumpRoute('/user/#/agent/AgentDataStatistic')"

/**
    * 跳转路由
    */
  public jumpRoute(path:string){
      if(location.href.includes(path)){
          return;
      }
      location.href=path;
  }
```