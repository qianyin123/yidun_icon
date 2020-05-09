# 用于易盾图标点选的代码

开发于 python3，依赖 opencv（带有sift算法的cv版本），依赖 pytorch

内附少量样本直接执行即可测试，直接显示标注好的图片。代码稍加修改就能拿到自己想要的坐标信息了。

项目大小仅 3M。因为定位的 yolo 算法的网络被压缩到很小，便于下载。

脚本算法已做简单兼容，兼容 cpu和gpu两个版本。