# PixCheese

像素吐司客户页。

访问链路：

客户页 -> EMQX `pixcheese/...` topic -> `tusi-emqx` 中间层 -> 内网 tusi 接码接口。

客户页不直接访问 tusi 服务器。
