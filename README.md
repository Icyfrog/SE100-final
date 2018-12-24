 # RWrite 简介
 ## 产品介绍
  目前中小学生的语文教育还是以识文断字为主，作业中重复内容较多；老师每天批改的作业量大，时间紧任务重，保证批改正确性的同时，还需要保证第二天能及时将作业结果反馈给学生。
  有关智能批改作业方面，目前市面上诞生的有英语作文在线批改系统“批改网”、教师在线批改作业系统及线上教育服务平台“伯索云学堂”等。同时有关手写字体识别方面，“讯飞开放平台”也在进行相关功能的实现。而在识别手写体错别字以及书写指导方面，目前网上技术还是空白。
  为了减轻教师工作量，同时能够给学生及时反馈作业情况，为学生提供个性化的教学指导，我们尝试开发名为RWrite的手写字体识别系统。主要包含以下功能：
（1）	智能批改：识别学生的手写字体，并经过筛选后选出其中的错别字，代替语文老师批改作业的工作，减轻老师负担；
（2）	及时反馈：学生在家中完成作业后，可以将图片（来源如扫描仪或者数码相机）上传至网络，由项目即时批改反馈，达到学习效率最高化；
 ## 背景调研
   在设计产品前，我们以中小学学生和教师家长为主要对象，以散发网络问卷的方式，调研了大众对自动批改作业的态度及意向。关于调研的具体结果请看 [survey.md](https://github.com/llIllIllIlllIll/SE100-final/blob/master/survey.md)。
 ## 设计思路
   框架方面我们用了Vue.js，使得整个界面的交互性设计非常容易。
 ## 打开方式
   因为这是一个比较小的项目，我们并没有选择搭建Vue的脚手架和npm工具。这个项目只需要下载压缩包并解压，打开index.html就可以看到完整的呈现。
   使用方式就是上传你需要识别的图片，然后点击识别，就会看见识别的结果。用户可以自行修改识别结果、添加评语、反馈错误。
