# loon-rules

Loon 远程分流规则，自用。

## 订阅地址

```
https://raw.githubusercontent.com/kunkkaCN/loon-rules/main/rules.list
```

在 Loon 中添加远程规则订阅，填入上面这个地址，更新订阅即可同步最新规则。

## 修改规则

直接编辑 `rules.list`，每行一条，格式为 `类型,域名,策略`，例如：

```
DOMAIN,example.com,DIRECT
DOMAIN-SUFFIX,example.org,香港时延优选
```

提交后，在 Loon 里更新订阅生效。

## 策略组说明

- `DIRECT`：直连
- `香港时延优选` / `兜底后备策略` / `日本手动策略`：Loon 中已有的策略组名，须与 Loon 配置里的名字完全一致
