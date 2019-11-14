# Internet网络结构
端系统通过接入ISP(access ISPs)连接到Internet
- 家庭，公司和大学ISPs
- 接入ISP必须进一步互连，这样任意两个主机才可以互相发送分组
- 当前某个Internet网络结构，无人能够给出精确描述。

## 每个接入ISP如何彼此互连？
- 每个ISP一一互连(复杂度O(n^2))
- 将每个接入ISP连接到一个国家或全球ISP中
- 中心ISP接入IXP进行互连
- 内容提供商网络(Google，microsoft)
    - 可运行自己的网络，就近为端用户提供服务