# NodeBB Plugin DB Search

A Plugin that lets users search posts and topics, use @node-rs/jieba to support Chinese.

Limitations: During testing, an issue arises when searching using only ONE single Chinese character. You can temporarily fix this by editing the '1' to '0' in the NodeBB source: [src/modules/search.js#L299](https://github.com/NodeBB/NodeBB/blob/514af5d657fda68c692b2b1fd1247e0a88b59f88/public/src/modules/search.js#L299).

## Installation

    npm install nodebb-plugin-dbsearch-rsjieba



