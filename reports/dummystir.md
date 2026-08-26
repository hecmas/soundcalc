# 📊 DummySTIR

How to read this report:
- Table rows correspond to security regimes
- Table columns correspond to proof system components
- Cells show bits of security per component
- Proof size estimates are indicative (1 KiB = 1024 bytes)

**Parameters:**
- Proof system: DEEP-ALI
- PCS: STIR
- Hash size (bits): 256
- Field: Goldilocks³
- Iterations (M): 5
- Folding factors (k_i): [4, 4, 4, 4, 4]
- Initial rate (ρ): $2^{-4}$
- Initial log-degree: 20
- Batch size: 200
- Batching: Powers
- Queries per iteration: [55, 31, 22, 17, 14]
- OOD samples per iteration: [1, 1, 1, 1]
- Total grinding overhead log2: 23.55
- Number of constraints: 500

**Proof Size:** 1463 KiB (expected) / 1487 KiB (worst case)

| regime | total | ALI | DEEP | OOD(i=1) | OOD(i=2) | OOD(i=3) | OOD(i=4) | batching | fin | fold(i=0) | shift(i=1) | shift(i=2) | shift(i=3) | shift(i=4) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UDR | 30 | 183 | 169 | 176 | 180 | 184 | 188 | 182 | 30 | 185 | 72 | 52 | 41 | 35 |
| JBR | 128 | 173 | 160 | 151 | 149 | 147 | 145 | 147 | 128 | 150 | 131 | 130 | 129 | 129 |
