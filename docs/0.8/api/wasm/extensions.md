---
layout: docu
redirect_from:
- docs/archive/0.8.1/api/wasm/extensions
selected: Client APIs
title: Extensions
---

Default [extensions](../../extensions/overview) currently enabled in DuckDB-Wasm are Parquet and FTS. HTTPFS is a specific re-implementation that comes bundled by default. 

JSON and Excel are build-time opt-in.

## Dynamic (= runtime) extension loading

Dynamic extension loading is currently experimental. Please participate in the [tracking issue](https://github.com/duckdb/duckdb-wasm/issues/1202).
