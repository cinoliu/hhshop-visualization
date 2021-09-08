
####  前序准备
你需要了解 [vue3.0](https://github.com/vuejs/vue-next)的新特性和Api方法后才开始熟悉本项目，大部分数据采用[Mock.js](https://github.com/nuysoft/Mock) 进行模拟，[axios](https://github.com/axios/axios)请求数据，最大还原了请求后台接口数据，由于[element-ui](https://github.com/ElemeFE/element) ,所以这里自己手写了几个项目中遇到的UI组件，正在持续更新中...




![](https://raw.githubusercontent.com/cinoliu/Big-data-visualization/master/img/1.jpg)
![](https://raw.githubusercontent.com/cinoliu/Big-data-visualization/master/img/2.jpg)


#### 系统架构
> 架构定义了项目的前端/中台/后端的组成

>  架构内容
![](https://raw.githubusercontent.com/cinoliu/Big-data-visualization/master/img/3.jpg)


#### 系统流程
> 系统流程定义了项目中的数据处理流程

>  系统流程
![](https://raw.githubusercontent.com/cinoliu/Big-data-visualization/master/img/4.jpg)




#### 功能

```
- 柱状图
- 饼图
- 词云图
- 漏斗图
- 水球图
- 折线图
- 仪表盘
- 雷达图
- 矩形树图
- 关系图
- 地图  --- 分布图
- 地图  --- 散点图
- 地图  --- 热力图
```

####  使用说明
```
- 首页时间自动轮播，每次时间切换都会调接口，所有的图数据都会刷新
- 首页点击时间轴切换时间
- 首页点击地图可以下钻到县  周围数据都会变，显示对应市县的
- 首页下钻后点击中间空白处或者左上角可以回到对应市县
- 点击两边的echarts图可以进去详情页
- 最右边的关系图点击可以下钻
- 点击地图右上角的图标可以切换地图类型
```
