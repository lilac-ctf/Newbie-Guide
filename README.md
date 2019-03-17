# Lilac CTF NewBie Guide



## Fast Q&A

**Q**：怎么学啊？

**A**：推荐的学习方式是：

```c
while(1) {
  看教程|书|其他阅读资源;
  做题;
  while(没做出来) {
    查资料;
    if (实在做不出来) {
      看writeup;
      复现;
      break;
    }
  }
  分享与总结;
}
```



**Q**：从哪里获取学习资料？

**A**：

 1. [ctf-wiki](https://ctf-wiki.github.io/ctf-wiki/) (也可以contribute)

 2. 大群群文件

 3. 上网搜索，github有大量优质资源

 4. 咨询学长

    ​	

**Q**：从哪个方向开始学

**A**：从哪个开始都可以，先扎进去再说



**Q**：有哪些适合的题目

**A**：

- [picoctf](https://picoctf.com) (PS: 把https://2018game.picoctf.com的2018换成其他年份可以访问之前的比赛题目)
- [jarvisoj](https://www.jarvisoj.com/challenges)
- 待补充



**Q**：PWN和WEB有什么区别

**A**：PWN是针对二进制程序中存在漏洞进行攻击，典型的是常说的缓冲区溢出；WEB是对WEB服务程序的漏洞进行利用以获取WEB服务器上的重要数据或控制权限。



**Q**：PWN和逆向有什么区别

**A**：PWN侧重于对软件的漏洞进行挖掘和利用；逆向侧重于理解或还原程序流程，从而进行"破解"。



**Q**：需要学什么语言

**A**：按需要学。供参考

```
Common {
	Required python  
}

WEB {
  Required javascript,
  Required php
}

Binary {
  Required assembly,
  Required C/C++,
  Optional C#, Java, Lua, golang, ...
}
```



**Q**：一周要学多长时间

**A**：按照自己的节奏来，学到即赚到



**Q**：...

**A**：...



-----

## Resource

### Website

- [ctf-wiki](https://ctf-wiki.github.io/ctf-wiki/)

- [awesome-ctf](https://github.com/apsdehal/awesome-ctf#tutorials)

- [search on github](https://github.com/search?q=awesome+ctf)
- 待补充



### Books to start with

- **WEB**
  - 待补充
- **BIN** (PWN/Reversing)
  - 《汇编语言》—王爽
  - 《深入理解计算机系统第三版》

- **PWN**
  - 《程序员的自我修养》
- **Reversing**
  - 《C++反汇编与逆向分析技术揭秘》
  - 《加密与解密》(Hard. Recommend for reference)
- **Crypto**
  - 《深入浅出密码学 常用加密技术原理与应用》





