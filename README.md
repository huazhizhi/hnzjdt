# 河南宗教自动答题 1.6   重要高质量更新！
### 最近更新 2021-11-30      V1.6
更新内容：

       1、重构了题目匹配机制，匹配成功率高达99.9%，无视试题加密，题目重复等问题   【由之前的模糊匹配改为精准匹配，效果惊人】
       
       2、解决了不同题的题目相同导致答案无法匹配的bug 【如：下列选项正确的是() 。这类题型可以完美匹配】
       
       3、完善了在线题库
       
       4、上传了答题的html页面，下载后修改【examination.js】这个文件的第161行 中的姓名改成你的，分数改成1亿
      alert("兽兽您的得分为95分,流水号：10047"+randomStr+",提交时间："+ currentFormatDate)
      可以实现点击提交按钮显示自定义分数
       
       5、windows可执行文件版本同步更新至v1.6
       
    
       
### 注：如果报错【{success:0,msg:'非法操作，涉嫌刷题1'}】  有两种情况：1、自行查看自己的IP地址是不是河南范围。2、这个ip在短时间提交了多份试卷，需要更换ip重新提交
       
       

#### 介绍
河南宗教自动答题,完成自动提交试题，经测试，得分均稳定在90以上，可以自行部署到云函数上，或者action，每天自动执行更省心，

#### 目录结构
-tool [工具目录]

    - dealData.py [文本处理]
    
    - driver.py [操作手]
    
    - fuzz.py [答案匹配]
    
-control.py [入口程序]



#### 使用说明
源码版本：
	编辑control.py，填入自己的信息，python control.py运行即可

exe版：
         双击运行
	 
	 
	 
#### 特别声明:
本仓库发布的hnzjdt项目中涉及的任何脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播,aqz236对于由此引起的任何隐私泄漏或其他后果概不负责。

请勿将hnzjdt项目的任何内容用于商业或非法目的，否则后果自负。

如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本。

以任何方式查看此项目的人或直接或间接使用hnzjdt项目的任何脚本的使用者都应仔细阅读此声明。aqz236保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或hnzjdt项目，则视为您已接受此免责声明。

您必须在下载后的24小时内从计算机或手机中完全删除以上内容。

您使用或者复制了本仓库且本人制作的任何代码或项目，则视为已接受此声明，请仔细阅读
您在本声明未发出之时点使用或者复制了本仓库且本人制作的任何代码或项目且此时还在使用，则视为已接受此声明，请仔细阅读

#### 题库项目 最近更新2021-11-28
 题库项目地址 https://github.com/aqz236/aqz236-hnzjtk
