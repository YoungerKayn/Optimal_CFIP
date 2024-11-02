[ tianshipapa ](https://github.com/tianshipapa)和
[ymyuuu](https://github.com/ymyuuu/BestDomain)
https://github.com/jc-lw/youxuanyuming


- 每3小时自动抓取  https://ip.164746.xyz 的优选ip，形成ip.txt 
- 还有js自动生成的https://cf.090227.xyz 
![image.png](https://rin.vcrr.us.kg/images/51e6dd9bbb99f98d3241509b804d98a4fc1fa5db.png)

- `caijiip.yml `文件夹里面改成你自己的，否则报错
![image.png](https://rin.vcrr.us.kg/images/0ddaaecae1242f12aadaa847662d56a23398cda5.png)
- `collect_ips.py`文件 这里是抓取优选IP的网站，如需要可自行修改
![image.png](https://rin.vcrr.us.kg/images/38a3d57288da468b17964664e54da54a4175ba0e.png)

# BestDomain 需要Cloudflare API令牌

- 这里修改你的二级域名开头
![image.png](https://rin.vcrr.us.kg/images/85362a2f5680355d4d73a2293ce82099c42e3308.png)
![image.png](https://rin.vcrr.us.kg/images/5def5f757d7a63978358e5a950714bed3dc6c213.png)
- 把上面的链接 修改成 你自己的链接，因为你抓取优选ip可能跟我不一样。
![image.png](https://rin.vcrr.us.kg/images/52f07d0b88279fb13694e1071d3184082408cf3d.png)



1. 创建 Cloudflare API 令牌
访问 [Cloudflare API Tokens](https://dash.cloudflare.com/profile/api-tokens)

2. 选择需要解析的域名，创建编辑 DNS 权限的` CF_API_TOKEN`
![image.png](https://rin.vcrr.us.kg/images/35feefcde1ed0cc08e430e419de73b892157d35c.png)


3. 在你的 GitHub 仓库中，设置 `CF_API_TOKEN `为你的 Cloudflare API 令牌
![image.png](https://rin.vcrr.us.kg/images/004eb6d2c8441cfa266129b3906e43e60bf99090.png)


4. 配置 GitHub Actions 定时任务
- 编辑 [.github/workflows/main.yml](.github/workflows/main.yml) 文件，设置 `cron` 表达式以定义任务运行时间
"# youxuanyuming" 

# 设置完成 
![image.png](https://rin.vcrr.us.kg/images/defa31617244ae82e89f05480be397eb3938f15e.png)
这里就是 运行完成，去ping出来的优选IP
![image.png](https://rin.vcrr.us.kg/images/8816d5204054629815ecf6add95e9e244849e85b.png)
