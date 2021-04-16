# ProguardCreater
混淆字典规则生成器

## 使用说明
### 一、创建字典
- 1、intellj IDEA 中打开项目
- 2、添加你需要的得字典规则的字符。
- 3、run main方法，即可得到混淆字典

### 二、把字典文件替换调 proguard.pro 中的外部字典引入
```java
# 指定外部模糊字典 proguard-chinese.txt 改为混淆文件名，下同
-obfuscationdictionary proguard-chinese.txt
# 指定class模糊字典
-classobfuscationdictionary proguard-chinese.txt
# 指定package模糊字典
-packageobfuscationdictionary proguard-chinese.txt
```
