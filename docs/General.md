# HTTP Basics
## Page 2

![L1_P1](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P1.png)

### Solution

按题给要求输入用户名，以“peterkim”为例

![L1_P2](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P2.png)

使用BurpSuite等工具抓包，点击“Go”后，可以看到页面出现如下字样

![L1_P3](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P3.png)

在BurpSuite中捕获如下HTTP请求和响应

![L1_P4](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P4.png)

## Page 3

![L1_P5](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P5.png)

### Solution

通过Page2中捕获的HTTP请求可以看出是POST类型，

直接点击“Go”按钮

![L1_P6](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P6.png)

查看捕获的HTTP请求，可以看到payload中包含magic number字段，填入对应数字即可

![L1_P7](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P7.png)

![L1_P8](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P8.png)

# HTTP Proxies

## Page 5

![L1_P9](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P9.png)

### Solution

开启BurpSuite拦截，点击“Submit”按钮，可以看到拦截到的POST类型的HTTP请求

![L1_P10](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P10.png)

按照题目要求，对请求进行修改，修改后的请求如下

![L1_P11](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P11.png)

将修改后的请求放行即可通过本题

![L1_P12](https://raw.githubusercontent.com/LS-King/WebGoat-Solution/main/pics/General/L1_P12.png)

