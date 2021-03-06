---
layout: post
title: "Release v1.4.3.0"
date: 2015-02-17 19:47:20 +0100
comments: true
categories: 
---



[Elastica v1.4.3.0](https://github.com/ruflin/Elastica/tree/v1.4.3.0) ([download](https://github.com/ruflin/Elastica/releases/tag/v1.4.3.0)). This release is compatible with elasticsearch 1.4.3.

## Dependencies

| Project | Version | Required |
|---------|---------|----------|
|[Elasticsearch](https://github.com/elasticsearch/elasticsearch/tree/v1.4.3)| 1.4.3 | yes
|[Elasticsearch mapper attachments plugin](https://github.com/elasticsearch/elasticsearch-mapper-attachments/tree/v2.4.2)|2.4.2|no
|[Elasticsearch thrift transport plugin](https://github.com/elasticsearch/elasticsearch-transport-thrift/tree/v2.4.1)|2.4.1|no
|[Elasticsearch geocluster facet plugin](https://github.com/zenobase/geocluster-facet/tree/0.0.12)|0.0.12|no



## Release Notes (changes.txt)

- Added Elastica\Query\MatchPhrase #599
- Added Elastica\Query\MatchPhrasePrefix #599
- Reset PHP 5.3 tests and enable compatibility for PHP 5.3 again
- Update elasticsearch compatibility to 1.4.3 #782
- Add support for scripted metric aggrations #780
- Added availability to specify regexp options in \Elastica\Filters\Regexp #583 #777
- Add HHVM as build in travis #649
- Fixed issue with OutOfMemory exception in travis builds #775
- Add support for filters aggregation #773
- Housekeeping, coding standard #764 
- Exception\ElasticsearchException now can be catched like all other exceptions as Exception\ExceptionInterface #762
