Qrcode Asin to Utf8

在工作中遇到了ASNI格式生成的二维码

Qrcode.js识别结果为乱码

所以修改了Qrcodejs

返回16进制结果

最后由Unicode转为Utf8格式

获取正常内容结果后，发现结果为全角，所以通过DS.js转为半角

当前img文件夹二维码不是Asni编码生成的

暂时不能提供此类二维码