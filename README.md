# 将压缩包伪装成其他文件,绕过无法上传/分享的限制
使用非常简单免费,并且失败概率极低.已经测试过5g大压缩包没有问题,简单好用,并且也能方便处理多个压缩包.持续更新.       
实现原理,通过修改文件头,使用可分享文件的文件头,达到让其误判的效果.       
如果选择文件后程序显示memory error后闪退，可能是因为内存容量不足（任务管理器-内存-已提交），请尝试：     
1更换大容量内存     
2增加虚拟内存容量（未测试）     
3使用低速版程序     
4使用分卷压缩，确保每个压缩包的大小都小于剩余可提交的内存容量     

###### 已知问题：输出后内存不会自动释放，需要手动关闭程序（不知道该怎么解决QAQ，会python的大佬救救我）
