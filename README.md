# FIWARE Cosmos

[![](https://nexus.lab.fiware.org/static/badges/chapters/processing.svg)](https://www.fiware.org/developers/catalogue/)
![License](https://img.shields.io/github/license/ging/fiware-cosmos-orion-flink-connector.svg)
[![](https://img.shields.io/badge/tag-fiware--cosmos-orange.svg?logo=stackoverflow)](http://stackoverflow.com/questions/tagged/fiware-cosmos)
<br/>
![Status](https://nexus.lab.fiware.org/static/badges/statuses/cosmos.svg)

The Cosmos Generic Enabler simplifies Big Data analysis of context data and integrates with some of the many popular Big
Data platforms.

Cosmos is a FIWARE Generic Enabler. Therefore, it can be integrated as part of any platform “Powered by FIWARE”. FIWARE
is a curated framework of open source platform components which can be assembled together with other third-party
platform components to accelerate the development of Smart Solutions.

This project is part of [FIWARE](https://www.fiware.org/). For more information check the FIWARE Catalogue entry for
[Context Processing, Analysis and Visualization](https://github.com/Fiware/catalogue/tree/master/processing).



## Table of Contents

-   [What is Cosmos?](#what-is-cosmos)
-   [Why use Cosmos?](#why-use-cosmos)
-   [Maintainers](#maintainers)
-   [Roadmap](#roadmap)
-   [Contributing](#contributing)
-   [License](#license)

---

## What is Cosmos?

The Cosmos Big Data Analysis GE is a set of tools that help achieving the tasks of Streaming and Batch processing over
context data. These tools are:

-   [Orion-Flink Connector (Source and Sink)](https://github.com/ging/fiware-cosmos-orion-flink-connector)
-   [Orion-Flink Connector Streaming Examples](https://github.com/ging/fiware-cosmos-orion-flink-connector-examples)
-   [Apache Flink Processing Engine](https://flink.apache.org/)
-   [Orion-Spark Connector (Source and Sink)](https://github.com/ging/fiware-cosmos-orion-spark-connector)
-   [Orion-Spark Connector Streaming Examples (work in progress)](https://github.com/ging/fiware-cosmos-orion-spark-connector)
-   [Apache Spark Processing Engine](https://spark.apache.org/)

## Why use Cosmos?

As the state of the real world changes, the entities representing your IoT devices are constantly changing. Big data
analysis allows for the study of datasets coming from your context data which are too large for traditional
data-processing software. You can apply predictive analysis or user behaviour analytics to extract meaningful
conclusions as to the state of your smart solution and bring value to your solution.


## Maintainers

[@sonsoleslp](https://github.com/sonsoleslp).

## Roadmap

### Short term

The following list of features are planned to be addressed in the short term, and incorporated in the next release of the product:

 * **NGSI-LD**: Achieve support for the NGSI Linked data format.

### Medium term

The following list of features are planned to be addressed in the medium term, typically within the subsequent release(s) generated in the next 9 months after next planned release:

 * **Docker images**: Provide FIWARE Docker images to facilitate the deployment of a complete big data processing scenario.

### Long term

The following list of features are proposals regarding the longer-term evolution of the product even though development of these features has not yet been scheduled for a release in the near future. Please feel free to contact us if you wish to get involved in the implementation or influence the roadmap:

 * **Apache Ranger and Atlas**: Study the suitability of using these technologies for streaming scenarios.

## Contributing

TBD


## License

Cosmos is licensed under [Affero General Public License (GPL) version 3](./LICENSE).

### Are there any legal issues with AGPL 3.0? Is it safe for me to use?

There is absolutely no problem in using a product licensed under AGPL 3.0. Issues with GPL (or AGPL) licenses are mostly
related with the fact that different people assign different interpretations on the meaning of the term “derivate work”
used in these licenses. Due to this, some people believe that there is a risk in just _using_ software under GPL or AGPL
licenses (even without _modifying_ it).

For the avoidance of doubt, the owners of this software licensed under an AGPL-3.0 license wish to make a clarifying
public statement as follows:

> Please note that software derived as a result of modifying the source code of this software in order to fix a bug or
> incorporate enhancements is considered a derivative work of the product. Software that merely uses or aggregates (i.e.
> links to) an otherwise unmodified version of existing software is not considered a derivative work, and therefore it
> does not need to be released as under the same license, or even released as open source.
