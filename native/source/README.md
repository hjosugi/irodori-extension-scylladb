# Native Source

The initial source snapshot was copied from `db/cassandra.rs` in the desktop app.

Source SHA-256: `8609b051e3c1d9c890b613266d04bb25a7350fcab8a0b81c64bc530ebc269fa9`.


This directory is a migration staging area for `irodori.scylladb`. The active native
ABI shim lives in `src/lib.rs`; engine-specific connect/query/metadata behavior
should move here as the connector runtime contract is wired into the desktop app.

Engine status from `knowledge/engines.json`: `wired`.
