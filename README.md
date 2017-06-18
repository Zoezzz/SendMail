# SendMail
Windows 环境下发送邮件到指定邮箱，编译环境为VS2010

1. timg.jpg 为附件发送测试图片， 若要测试其他文件，则在程序中修改为你的当前路径，如果不需要发送附件，将smtp.AddAttachment(filePath)一句注释掉。
2. 采用的是SMTP协议，所以指定的发送邮箱需要开启POP3/SMTP/IMAP服务，（这一点很重要，至少要开启SMTP服务），否则会发送不成功。
3. 编译环境为VS2010，程序功能基本与编译环境无关。

haha have fun
