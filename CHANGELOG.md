# TOML config changelog

toml format changes, newest-first.

### 2026-07-23 — Protocol family
- moved `protocol_family` from the `[zkevm]` section to each `[[circuits]]` section, so a VM can mix proof-system families across circuits

### 2026-05-02 — WHIR
- allow custom folding factors in WHIR

### 2026-04-20 (`1d4371a`) — Lookups
- removed `alphabet_size_H`

### 2026-03-16 (`b3f6610`) — FRI
- rename `grinding_bits_batching` → `grinding_batching_phase`
