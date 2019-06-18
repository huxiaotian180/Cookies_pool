# Cookies_pool
Flask+Redis维护Cookies池

# 为什么要用Cookies池？

网站需要登录才可爬取，例如新浪微博

爬取过程中如果频率过高会导致封号

需要维护多个账号的Cookies池实现大规模爬取

# Cookies池的要求

自动登录更新

定时验证筛选

提供外部接口

# Cookies池架构

![](https://github.com/huxiaotian180/ImageCache/raw/master/Loge/cookies.png)




