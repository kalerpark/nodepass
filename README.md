# nodepass
本脚本提供了简单易用的 master 模式，即 API 模式的安装、配置和管理功能，
NodePass 通用TCP/UDP隧道解决方案，免配置单文件多模式，采用控制数据双路分离架构，内置零延迟自适应连接池，实现跨网络限制的快速安全访问。
本脚本提供了简单易用的 master 模式，即 API 模式的安装、配置和管理功能
多系统支持：兼容 Debian、Ubuntu、CentOS、Fedora、Alpine、Arch 和 OpenWrt 等多种 Linux 发行版
交互式部署

下载并执行脚本：
bash <(wget -qO- https://run.nodepass.eu/np.sh)
或
bash <(curl -sSL https://run.nodepass.eu/np.sh)

按照界面提示选择语言（默认中文）
在主菜单中选择"安装 NodePass"
根据提示输入以下信息：
服务器 IP（默认为 127.0.0.1）
端口号（1024-65535，留空则使用 1024-8192 的随机端口）
API 前缀（默认为 api）
TLS 模式（0: 无加密, 1: 自签名证书, 2: 自定义证书）
等待安装完成
部署后的快捷指令

安装完成后，系统会创建 np 快捷指令，可以通过以下方式使用：

np - 显示菜单
np -i - 安装 NodePass
np -u - 卸载 NodePass
np -v - 升级 NodePass
np -o - 切换服务状态（开启/停止）
np -k - 更换 NodePass API key
np -s - 显示 NodePass API 信息
np -h - 显示帮助信息
