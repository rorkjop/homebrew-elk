# Homebrew ELK

This repository contains Homebrew formulae for Elasticsearch, Logstash, and
Kibana version 7.1.0.

## Installation

In order to get going, you need to tap the repository with:

`$ brew tap rorkjop/homebrew-elk`

## Elasticsearch

To install Elasticsearch run:

`$ brew install rorkjop/elk/elasticsearch`

## Kibana

Installing Kibana takes a very long time because everything is built from
source. Don't do it unless you absolutely need the latest version. Also, during
the installation you'll get an error message saying:

```
# Don't panic. Everything is fine.

curl: (22) The requested URL returned error: 404 Not Found
Error: Failed to download resource "kibana"
Download failed: https://homebrew.bintray.com/bottles/kibana-7.1.0.mojave.bottle.tar.gz
```

With that out of the way, run the following command to perform the installation:

`$ brew install rorkjop/elk/kibana`

