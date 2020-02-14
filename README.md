# Autocompletion-erp5  
![GitHub file size in bytes](https://img.shields.io/github/size/Nutarb/Autocompletion-erp5?style=flat-square) 
![GitHub](https://img.shields.io/github/license/Nutarb/Autocompletion-erp5?style=flat-square)
## 1. 自问自答
>Q:你要做什么？  
>A:尝试浏览器扩展开发，提高事务类工作处理效率。  
  
>Q:不够具体，请问本次要解决的问题是？  
>A:本次目标是提高ERP任务单编写效率，如果你跟我一样觉得申请任务单存在重复性工作，那这就是一个问题。  
  
>Q:我不承认这是个问题，我觉得这并不麻烦，~~你说你妈呢~~？  
>A:谢谢，再见！  
  
>Q:我承认存在问题，可以讲一下解决思路？  
>A:好的！  
  
>Q:为什么选择自己做？  
>A:1.想自己动手 2.脚本是原生js，有研究价值。综合考虑以上2点，有投入价值。  
  
>Q:为什么选择chrome扩展的形式？  
>A:安装方便，运行环境稳定，比之前用python爬的速度更快、更安全  
  
>Q:使用对象是？  
>A:“感觉ERP代发任务单不太方便。主要是设计上有缺陷：指派人没有编辑权限（而制单人有，但是要编辑，需要指派人取消对日志的确认）；所以后续建议指派人和制单人是同一人。”  中描述的制单人。
  
>Q:数据来源？  
>A:从本地读取（不太可行，退而求其次的策略：拖拽、上传）  
读取excel（不太可行，时间紧张，先用纯文本，直接导出.csv。wps表格null导出的会有“”占位吗？  
方法1：插件包含拖拽、上传，直接传文本（计划中…）  
方法2：单独部署一个含excel内容的web页，跨域请求  
方法3：ajax连接数据库（要学的有点多？）  
  
>Q:关于维护？
>A:程序本体更新：插件版本升级（尽可能少）  
配置信息更新：从其他web页取所有配置信息  
