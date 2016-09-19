%%重在掺和，慎重参考……
ejabberd 项目默认使用的是xmpp协议，但某些蛋疼的需求需要支持json 协议的支持，
ejabberd 项目中自带的rfc4627.erl 有个json 的解析和转换，但不够完整，然后我顺便
写了几个方法支持了 ejabberd 项目中 xml 与 json 的转换。 