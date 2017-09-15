---
layout: post
title:  "ElasticSearch - Term Level Queries"
date:   2017-09-15 +0800
categories: learning notes
---
Different from full-text queries, term level queries operates on specific terms.
For QueryBuilder (Java) There are serval types of queries, like:

`termsQuery` with field, value

`rangeQuery` with field, from, to

`existQuery` with field




`boolQuery` will be discussed separately




Check out [this][docs1] for more info.

[docs1]: https://www.elastic.co/guide/en/elasticsearch/client/java-api/current/java-term-level-queries.html
