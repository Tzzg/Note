## docker 访问宿主机
有时候就需要在docker容器里访问宿主机提供的服务。
例如容器里的应用需要访问宿主机的mysql服务。

### 方案一：
宿主机执行ifconfig
``
ifconfig | grep docker -A 2
``
会看到docker0那个ip，可以使用来访问宿主机
