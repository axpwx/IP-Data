# IP-Data
基于全球ASN数据和部分厂商的公示数据提取的IDC和公有云服务IP(国内包含了极少量企业专线)，相邻或包含的IP段进行了合并。  
这些IP通常不会分配给终端用户使用，可用于辅助人机检查等场景。  

数据每天检查一次，如有更新会自动提交。  

## 所有IDC和云厂商IP  
All-In-One: ([ipv4](/provider/all-cidr-ipv4.txt?raw=1)) ([ipv6](/provider/all-cidr-ipv6.txt?raw=1))  

## 主要公有云厂商的单独列表  
#### 国内云厂商  
| provider | ipv4 | ipv6 |
|----|----|----|
| 阿里云 | [ipv4](/provider/aliyun-cidr-ipv4.txt?raw=1) | [ipv6](/provider/aliyun-cidr-ipv6.txt?raw=1) |
| 腾讯云 | [ipv4](/provider/tencent-cidr-ipv4.txt?raw=1) | [ipv6](/provider/tencent-cidr-ipv6.txt?raw=1) |
| 华为云 | [ipv4](/provider/huawei-cidr-ipv4.txt?raw=1) | [ipv6](/provider/huawei-cidr-ipv6.txt?raw=1) |
| ulcoud | [ipv4](/provider/ucloud-cidr-ipv4.txt?raw=1) | [ipv6](/provider/ucloud-cidr-ipv6.txt?raw=1) |
| 金山云 | [ipv4](/provider/ksyun-cidr-ipv4.txt?raw=1) | [ipv6](/provider/ksyun-cidr-ipv6.txt?raw=1) |
| 百度云 | [ipv4](/provider/baidu-cidr-ipv4.txt?raw=1) | [ipv6](/provider/baidu-cidr-ipv6.txt?raw=1) |
| 京东云 | [ipv4](/provider/jdcloud-cidr-ipv4.txt?raw=1) | [ipv6](/provider/jdcloud-cidr-ipv6.txt?raw=1) |

#### 国外云厂商  
| provider | ipv4 | ipv6 |
|----|----|----|
| AWS | [ipv4](/provider/aws-cidr-ipv4.txt?raw=1) | [ipv6](/provider/aws-cidr-ipv6.txt?raw=1) |
| Azure | [ipv4](/provider/azure-cidr-ipv4.txt?raw=1) | [ipv6](/provider/azure-cidr-ipv6.txt?raw=1) |
| Google Cloud | [ipv4](/provider/googlecloud-cidr-ipv4.txt?raw=1) | [ipv6](/provider/googlecloud-cidr-ipv6.txt?raw=1) |
| Oracle Cloud | [ipv4](/provider/oracle-cidr-ipv4.txt?raw=1) | [ipv6](/provider/oracle-cidr-ipv6.txt?raw=1) |
| IBM Cloud(SoftLayer) | [ipv4](/provider/ibmcloud-cidr-ipv4.txt?raw=1) | [ipv6](/provider/ibmcloud-cidr-ipv6.txt?raw=1) |
| DigitalOcean | [ipv4](/provider/digitalocean-cidr-ipv4.txt?raw=1) | [ipv6](/provider/digitalocean-cidr-ipv6.txt?raw=1) |
| linode | [ipv4](/provider/linode-cidr-ipv4.txt?raw=1) | [ipv6](/provider/linode-cidr-ipv6.txt?raw=1) |
| cloudflare | [ipv4](/provider/cloudflare-cidr-ipv4.txt?raw=1) | [ipv6](/provider/cloudflare-cidr-ipv6.txt?raw=1) |

## 数据源  
- https://bgp.he.net/  
- APNIC, ARIN, RIPE ...  
- 部分国外云厂商基于其公示数据
