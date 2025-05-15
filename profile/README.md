🌪️ Vortex
=========

📚 [Documentation](https://docs.vortex.dev/) | 📊 [Performance Benchmarks](https://bench.vortex.dev)

## Overview

Vortex is a next-generation columnar file format and toolkit designed for high-performance data analytics. It provides:

- **⚡️ Blazing Fast Performance**
    - 100-200x faster random access reads than Apache Parquet
    - 2-10x faster scans with similar compression ratios and write throughput
    - Efficient support for wide tables with zero-copy/zero-parse metadata

- **🔧 Extensible Architecture**
    - Modeled after Apache DataFusion's extensible approach
    - Pluggable encoding system
    - Zero-copy compatibility with Apache Arrow

## Project Information

### License

Licensed under the Apache License, Version 2.0

### Governance

Vortex is an independent open-source project and not controlled by any single company. The Vortex Project
is a sub-project of the Linux Foundation Projects. The governance model is documented in 
[CONTRIBUTING.md](CONTRIBUTING.md) and is subject to the terms of the [Technical Charter](https://vortex.dev/charter.pdf).

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Acknowledgments 🏆

This project builds upon groundbreaking work from the academic and open-source communities:

### Key Research Papers

- [BtrBlocks](https://www.cs.cit.tum.de/fileadmin/w00cfj/dis/papers/btrblocks.pdf) - Efficient columnar compression
- [FastLanes](https://www.vldb.org/pvldb/vol16/p2132-afroozeh.pdf) - High-performance integer compression
- [FSST](https://www.vldb.org/pvldb/vol13/p2649-boncz.pdf) - Fast random access string compression
- [ALP](https://ir.cwi.nl/pub/33334/33334.pdf) - Adaptive lossless floating-point compression
- [Procella](https://dl.acm.org/citation.cfm?id=3360438) - YouTube's unified data system
- [Cloud Object Storage Analytics](https://www.durner.dev/app/media/papers/anyblob-vldb23.pdf) - High-performance
  analytics
- [ClickHouse](https://www.vldb.org/pvldb/vol17/p3731-schulze.pdf) - Fast analytics for everyone

### Open Source Inspiration

- [Apache Arrow](https://arrow.apache.org) & [Apache DataFusion](https://github.com/apache/datafusion)
- [parquet2](https://github.com/jorgecarleitao/parquet2) by Jorge Leitao
- [DuckDB](https://github.com/duckdb/duckdb)
- [Velox](https://github.com/facebookincubator/velox) & [Nimble](https://github.com/facebookincubator/nimble)

### Trademarks

Copyright © Vortex a Series of LF Projects, LLC
For web site terms of use, trademark policy and other project policies please see https://lfprojects.org

---
*Thanks to all contributors who have shared their knowledge and code with the community! 🚀*

