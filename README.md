# maibot-ops-releases

maibot-ops 的发行物与签名更新包。只放 release,不放源码。

源码仓:`wsolarq11/maibot-ops`(私有)。

更新包由 `mygo build -upload` 生成,Ed25519 签名。已安装的 maibot-ops 只接受
用对应私钥签名的更新;私钥不在本仓,也不在任何仓库里。
