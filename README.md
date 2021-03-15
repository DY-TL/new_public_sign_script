1.  京东水果([jd_fruit.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_fruit.js))
2.  东东萌宠([jd_pet.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_pet.js))
3.  宠汪汪([jd_joy.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_joy.js))
4.  种豆得豆([jd_plantBean.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_plantBean.js))
5.  天天加速([jd_speed.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_speed.js))
6.  摇钱树([jd_moneyTree.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_moneyTree.js))
7.  宠汪汪兑换奖品([jd_joy_reward.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_joy_reward.js))
8.  取关京东店铺和商品([jd_unsubscribe.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_unsubscribe.js))
9.  京小超([jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_superMarket.js))
10. 京小超领蓝币(兑换京豆)([jd_blueCoin.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_blueCoin.js))
11. 宠汪汪偷好友狗粮与积分([jd_joy_steal.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_joy_steal.js))
12. 进店领豆([jd_shop.js](https://raw.githubusercontent.com/lxk0301/scripts/master/jd_shop.js))


 - 使用教程暂且可看 [这里](githubAction.md)

#### 注：以上三种运行机制都是nodejs，故您需仔细阅读下面几点

  cookie不要！不要！不要！填写到 [jdCookie.js](https://github.com/lxk0301/scripts/blob/master/jdCookie.js) 里面
   
  - 获取京东cookie教程可参考 [浏览器获取京东cookie教程](https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie.md)
 

#### 4个京东账号的Qumutumult X cron设置示例(5分钟为间隔)

```
[task_local]
#切换会话
30,59 1-23 * * * https://raw.githubusercontent.com/chavyleung/scripts/master/box/switcher/box.switcher.js, tag=切换会话, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/BOXJS.png, enabled=true
#京东摇钱树
25,56 */2 * * * https://raw.githubusercontent.com/lxk0301/scripts/master/jd_moneyTree.js, tag=京东摇钱树, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/moneyTree.png, enabled=true
#京东宠汪汪
20,51 */3 * * * https://raw.githubusercontent.com/lxk0301/scripts/master/jd_joy.js, tag=京东宠汪汪, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdww.png, enabled=true
#京东天天加速
15,46 */4 * * * https://raw.githubusercontent.com/lxk0301/scripts/master/jd_speed.js, tag=京东天天加速, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdttjs.png, enabled=true
#东东农场
10,41 7-19/6 * * * https://raw.githubusercontent.com/lxk0301/scripts/master/jd_fruit.js, tag=东东农场, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdsg.png, enabled=true
#京东萌宠
5,36 6-18/6 * * * https://raw.githubusercontent.com/lxk0301/scripts/master/jd_pet.js, tag=京东萌宠, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdmc.png, enabled=true
#种豆得豆
0,31 6-23/2 * * * https://raw.githubusercontent.com/lxk0301/scripts/master/jd_plantBean.js, tag=种豆得豆, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdzd.png, enabled=true
```

#### 最后，农场萌宠种豆得豆互相助力可进此[telegram讨论组](https://t.me/JD_fruit_pet)

### 特别感谢(排名不分先后)：
* [@NobyDa](https://github.com/NobyDa)

* [@chavyleung](https://github.com/chavyleung)

* [@liuxiaoyucc](https://github.com/liuxiaoyucc)

* [@Zero-S1](https://github.com/Zero-S1)

* [@uniqueque](https://github.com/uniqueque)


* [@nzw9314](https://github.com/nzw9314)

