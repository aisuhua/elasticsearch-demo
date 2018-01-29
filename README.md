# elasticsearch-demo

学习笔记

## API

### _cat

```
/_cat/shards
/_cat/shards/{index}
/_cat/indices
/_cat/indices/{index}
```

### _node

```
/_nodes
```

### _settings

```
/_settings
/my_index/_settings
/my_index/_settings?include_defaults=true
/my_index/my_type/_mappings
```



## Related

- [Elasticsearch高级搜索排序（ 中文+拼音+首字母+简繁转换+特殊符号过滤）](http://www.cnblogs.com/clonen/p/6674888.html)
- [将 ELASTICSEARCH 写入速度优化到极限](https://www.easyice.cn/archives/207)
- [ELASTICSEARCH 写流程](https://www.easyice.cn/archives/180)
- [ElasticStack系列之九 & master、data 和 client 节点](https://www.cnblogs.com/liang1101/p/7284205.html)
- [分片内部原理](https://www.elastic.co/guide/cn/elasticsearch/guide/current/inside-a-shard.html)
- [Index Modules](https://www.elastic.co/guide/en/elasticsearch/reference/master/index-modules.html)
- [Update Indices Settings](https://www.elastic.co/guide/en/elasticsearch/reference/master/indices-update-settings.html)
- [Index Templates](https://www.elastic.co/guide/en/elasticsearch/reference/master/indices-templates.html)
- [Index Aliases](https://www.elastic.co/guide/en/elasticsearch/reference/current/indices-aliases.html)
