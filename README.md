# codeforces-reverse-proxy
使用cloudflare的边缘计算服务workers反向代理codeforces，支持登录，提交，浏览题目

demo：https://cf.sunxiaochuannmsl.workers.dev/

# 使用方法

1.把cf.js里32 33行里的 <YOUR-SUBDOMAIN> 改成你自己的cloudflare的子域名，就是aaa.bbb.workers.dev里的bbb

2.在cloudflare里创建三个运行JavaScript的worker，分别把三个js文件作为源代码然后deploy。
