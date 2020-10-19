[![CircleCI](https://circleci.com/gh/o19s/RankyMcRankFace.svg?style=svg)](https://circleci.com/gh/o19s/RankyMcRankFace)

[ ![Download](https://api.bintray.com/packages/o19s/RankyMcRankFace/RankyMcRankFace/images/download.svg) ](https://bintray.com/o19s/RankyMcRankFace/RankyMcRankFace/_latestVersion)

This project is [OpenSource Connections](http://opensourceconnections.com) API-compatible fork of Ranklib, deployed on Maven, with various improvements making it easier to integrate with the [Elasticsearch Learning to Rank Plugin](http://github.com/o19s/elasticsearch-learning-to-rank).

It is under the `com.o19s:RankyMcRankFace` Maven namespace.

## Ranklib

Ranklib is an open source learning to rank project hosted on [sourceforge](sourceforge.net/p/lemur/wiki/RankLib/) as part of the Lemur project. You can read the latest Ranklib Readme [here](readme.txt).

## Improvements over Ranklib

- Performance improvement reading in models, needed for the [Elasticsearch Learning to Rank Plugin](http://github.com/o19s/elasticsearch-learning-to-rank)
- During training: outputs impact (total error reduced) of each feature

bump.
