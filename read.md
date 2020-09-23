**git分支管理**

dev分支用于开发测试，master主分支用于线上

每次测试 merge master分支兼容master分支 推送测试

总测试完成 切到master分支 merge dev分支 推送主分支


**配置文件管理**

如果配置信息分开发和测试版本，则需要把配置信息配置到.env文件，

