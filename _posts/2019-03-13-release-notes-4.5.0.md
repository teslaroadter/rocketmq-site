---
title: "Release Notes - Apache RocketMQ - Version 4.5.0"
categories:
  - Release_Notes
tags:
  - Release_Notes
  - RocketMQ
  - Version
---

Below is a summary of the issues addressed in the 4.5.0 release of RocketMQ. For full documentation of the release, a guide to get started, please refer to <a href='/docs/quick-start/'>Quick Start</a>.


<h2> Download the 4.5.0 release</h2>
    
* Source: [rocketmq-all-4.5.0-source-release.zip](https://www.apache.org/dyn/closer.cgi?path=rocketmq/4.5.0/rocketmq-all-4.5.0-source-release.zip) [[PGP](https://www.apache.org/dist/rocketmq/4.5.0/rocketmq-all-4.5.0-source-release.zip.asc)] [[MD5](https://www.apache.org/dist/rocketmq/4.5.0/rocketmq-all-4.5.0-source-release.zip.md5)] [[SHA1](https://www.apache.org/dist/rocketmq/4.5.0/rocketmq-all-4.5.0-source-release.zip.sha1)]
* Binary: [rocketmq-all-4.5.0-bin-release.zip](https://www.apache.org/dyn/closer.cgi?path=rocketmq/4.5.0/rocketmq-all-4.5.0-bin-release.zip) [[PGP](https://www.apache.org/dist/rocketmq/4.5.0/rocketmq-all-4.5.0-bin-release.zip.asc)] [[MD5](https://www.apache.org/dist/rocketmq/4.5.0/rocketmq-all-4.5.0-bin-release.zip.md5)] [[SHA1](https://www.apache.org/dist/rocketmq/4.5.0/rocketmq-all-4.5.0-bin-release.zip.sha1)]

## New Fearture
<ul>
<li>[<a href='https://github.com/apache/rocketmq/pull/1046'>ISSUE-1046</a>] -  Support multiple replicas for RocketMQ.
</li>
</ul>

## Improvement
<ul>
<li>[<a href='https://github.com/apache/rocketmq/pulls?utf8=✓&q=is%3Apr+is%3Amerged+RIP-9'>RIP-9</a>] -  Provide RocketMQ Developer's Guide in English and Chinese
.
</li>
<li>[<a href='https://github.com/apache/rocketmq/pulls?utf8=✓&q=is%3Apr+is%3Amerged+RIP-10'>RIP-10</a>] -  Add unit test cases.
</li>
<li>[<a href='https://github.com/apache/rocketmq/issues/608'>ISSUE-608</a>] -  Polish the example of message filter.
</li>
<li>[<a href='https://github.com/apache/rocketmq/pull/742'>ISSUE-742</a>] -  Change log level in TransactionalMessageServiceImpl.
</li>
<li>[<a href='https://github.com/apache/rocketmq/issues/776'>ISSUE-776</a>] -  Make mqadmin usage information more friendly.
</li>
</ul>

## Bug
<ul>
<li>[<a href='https://github.com/apache/rocketmq/issues/762'>ISSUE-762</a>] -  Fix defaultAsyncSenderExecutor not shutdown when DefaultMQProducerImpl shutdown.
</li>
<li>[<a href='https://github.com/apache/rocketmq/issues/789'>ISSUE-789</a>] -  Fix a NullPointerException in the PlainAccessValidator#parse().
</li>
</ul>
                                        
            


