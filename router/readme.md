VUE REACT SPA Single Page Application 应用体验更好 页面会白一下
在传统的网页开发中 链接把网站组织起来 重新加载一个新的页面，发送一个新的http请求
/about req res 过程
req /about
时间 网路传输时间,01二进制, 二进制对应着电频信号 光速 + node/java/python 后端代码
，查数据库时间，把html返回回去 = 白屏时间 100-200
1.5s 用户就会离开，0.1s 1000w利润
res /about
路由是独立的
- 网站MVC => 应用(Vue App)体验产生路由  白屏问题?
  Vue Router 就来了
  - hashRouter
    #/shop #/
    优点是 ie8以上都支持
    缺点是:路由不纯粹， /shop 
    HistoryRouter history 历史的 /shop 访问的历史 记录
    VUERouter 两种实现方式 = HashRouter(兼容性) + HistroyRouter(不会产生歧义，移动端兼容性还是没有问题的)




