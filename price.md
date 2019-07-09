# 计费

{{indexmenu_n>45}}

**产品价格**

<table>
<thead>
<tr class="header">
<th>归档存储</th>
<th></th>
<th>备注</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>存储空间</td>
<td>0.002元/GB/天</td>
<td>根据用户每天的使用量<br />
按天收费，第二天统计<br />
前一天用量和费用</td>
</tr>
<tr class="even">
<td>数据激活</td>
<td>0.06元/GB/次</td>
<td>:::</td>
</tr>
<tr class="odd">
<td>数据删除</td>
<td>未满15日按0.06元/GB，超过15日免费</td>
<td>:::</td>
</tr>
<tr class="even">
<td>API请求</td>
<td>0.01元/万次</td>
<td>:::</td>
</tr>
<tr class="odd">
<td>数据传入</td>
<td>免费</td>
<td>:::</td>
</tr>
<tr class="even">
<td>下载流量<br />
（阶梯价）</td>
<td>0 - 1TB， 0.45元/GB</td>
<td>:::</td>
</tr>
<tr class="odd">
<td>:::</td>
<td>1 - 10TB， 0.40元/GB</td>
<td>:::</td>
</tr>
<tr class="even">
<td>:::</td>
<td>10 - 50TB， 0.36元/GB</td>
<td>:::</td>
</tr>
<tr class="odd">
<td>:::</td>
<td>50 - 100TB， 0.32元/GB</td>
<td>:::</td>
</tr>
<tr class="even">
<td>:::</td>
<td>100TB以上， 0.28元/GB</td>
<td>:::</td>
</tr>
</tbody>
</table>

注：
UArchive空间区分地域(北京、广州)，各地域价格相同。

## 计费说明

归档存储按照存储容量、激活容量（数据取回）、数据删除（不满15日时收取）、下载流量和API请求次数等多个维度进行计费。

### 存储容量计费说明

存储容量按天进行结算与扣减，单价0.002元/GB/天。购买时会自动四舍五入取整到100GB\*天。

### 激活容量计费说明

归档存储的定位是冷存储。当冷存储被访问而激活时，会收取激活费用（数据取回）。激活容量按天进行结算与扣减，单价0.06元/GB/次，一次激活有效期为1天。1天内多次下载不需要再次激活。

### 数据删除计费说明

归档存储的定位是冷存储，长期保存、极少访问。保存期未满15日的数据，删除时会额外收取一笔删除费用，单价0.06元/GB。保存时间达到15日后，删除时不收取任何费用。

### 下载流量计费说明

归档存储的下流流量收费法则，目前同UFile相同，为阶梯定价。每日下载流量越多，单价越低。下载流量按天进行结算与扣减。

### API请求次数计费说明

API请求次数按天进行结算与扣减，单价0.01元/万次。购买时自动四舍五入取整到万次。