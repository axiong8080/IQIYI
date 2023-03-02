# IQIYI
IQIYI AUTOMATIC SCRIPT
爱奇艺自动签到脚本

爱奇艺会员签到脚本
更新时间: 2022.1.21
脚本兼容: QuantumultX, Surge4, Loon, JsBox, Node.js
获取 Cookie 说明：
打开爱奇艺 App 后(AppStore 中国区)，点击"我的", 如通知成功获取 cookie, 则可以使用此签到脚本.
获取 Cookie 后, 请将 Cookie 脚本禁用并移除主机名，以免产生不必要的 MITM.
脚本将在每天上午 9:00 执行, 您可以修改执行时间。
如果使用 Node.js, 需自行安装'request'和'string-random'模块. 例: npm install request -g
JsBox, Node.js 用户抓取 Cookie 说明：
开启抓包, 打开爱奇艺 App 后(AppStore 中国区)，点击"我的" 返回抓包 App 搜索请求头关键字 将 cookie 全部字段写入 cookie
提取字母数字混合字段, 到&结束, 填入以下单引号内即可.
