# BirthdayPrompter
最近写了个生日提醒的东西，用Python写的，目前只在本机上运行，没有服务器。
Data.xlsx为数据，保存的是注册的信息和用户保存的朋友生日。main.py是给用户使用的，用户通过这个程序注册登录查询生日和保存生日。BirthdayPrompter.py是放在服务器上的（目前就是放在本机里），每天运行一次，他会检测所以用户及他们保存的所以生日，如果明天有人要生日了会给用户的邮箱发一封邮件提醒。
