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

### _cluster

```
/_cluster/health
/_cluster/health?level=shards
```


### _settings

```
/_settings
/my_index/_settings
/my_index/_settings?include_defaults=true
/my_index/my_type/_mappings
```

### _count

```
/my_index/_count
```

### _analyze

```
/_analyze?analyzer=standard&text=suhua is a good boy
/_analyze?analyzer=english&text=suhua is a good boy 
/my_index/_analyze?field=name&text=Black-cats
```

## Plugins

- [elasticsearch-analysis-ik](https://github.com/medcl/elasticsearch-analysis-ik)
- [elasticsearch-analysis-pinyin](https://github.com/medcl/elasticsearch-analysis-pinyin)

## Articles

- [Elasticsearch高级搜索排序（ 中文+拼音+首字母+简繁转换+特殊符号过滤）](http://www.cnblogs.com/clonen/p/6674888.html)
- [将 ELASTICSEARCH 写入速度优化到极限](https://www.easyice.cn/archives/207)
- [ELASTICSEARCH 写流程](https://www.easyice.cn/archives/180)
- [ElasticStack系列之九 & master、data 和 client 节点](https://www.cnblogs.com/liang1101/p/7284205.html)
- [分片内部原理](https://www.elastic.co/guide/cn/elasticsearch/guide/current/inside-a-shard.html)
- [Index Modules](https://www.elastic.co/guide/en/elasticsearch/reference/master/index-modules.html)
- [Update Indices Settings](https://www.elastic.co/guide/en/elasticsearch/reference/master/indices-update-settings.html)
- [Index Templates](https://www.elastic.co/guide/en/elasticsearch/reference/master/indices-templates.html)
- [Index Aliases](https://www.elastic.co/guide/en/elasticsearch/reference/current/indices-aliases.html)
- [cat APIs](https://www.elastic.co/guide/en/elasticsearch/reference/current/cat.html)
- [Cluster APIs](https://www.elastic.co/guide/en/elasticsearch/reference/current/cluster.html)
- [Tune for indexing speed](https://www.elastic.co/guide/en/elasticsearch/reference/6.1/tune-for-indexing-speed.html)

## Books

- [Elasticsearch: 权威指南](https://www.elastic.co/guide/cn/elasticsearch/guide/current/index.html)
- [Elasticsearch 5.4 中文文档](http://cwiki.apachecn.org/display/Elasticsearch/Index)
