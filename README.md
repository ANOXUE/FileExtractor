# FileExtractor
文件提取器

本工具采用python tkinter编写打包，适用于windows系统。支持对文本文件内容进行一些提取和处理,主要用于辅助处理ip和安全测试数据，严禁用于非法用途！

免责声明：本人坚决反对利用测试工具进行犯罪的行为，本工具禁止用于任何非法用途。如有任何人凭此做何非法事情，均于作者无关，特此声明。

功能支持:

1.对IP、域名、url进行提取（域名基于顶级后缀匹配，如遇无法匹配请将顶级域名添加至domains.txt文件）

2.对敏感信息（邮箱，手机号，身份证）进行提取

3.对IP段进行遍历，支持IP和IP段（‘192.168.0.1-2’‘192.168.0.1-192.168.0.2’‘192.168.0.1/32’3种格式）且按行分隔排列的文本文件

4.‘Text’菜单支持文本框内容复制、粘贴和行去重

5.‘IP-tool’支持对文本框纯IP数据的排序、归拢和去除255和0的地址

6.支持黑白主题
