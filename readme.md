Tracer是一个基于Django的轻量级bug&任务追踪管理平台，目的是让bug追踪更简单、高效、便捷，提供安全、稳定的数据保障，将项目管理与团队协作完美地结合在一起。。。

Overview
Tracer使用了Django自带的数据库SQLite储存了用户过程中的产生的基本信息，诸如注册信息、项目信息等，文件上传利用了腾讯云的对象存储（cos），对于某些必要的缓存，则利用Redis进行缓存处理，如短信注册、session缓存。


