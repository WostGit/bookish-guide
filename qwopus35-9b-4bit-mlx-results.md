# Qwopus3.5 9B 4-bit MLX benchmark

Status: `finished`
Model: `Jackrong/MLX-Qwopus3.5-9B-v3-4bit`
Started: `2026-05-30T04:32:51Z`
Updated: `2026-05-30T04:34:21Z`
Runner: `GitHub Actions 1000004789 macOS ARM64`
Platform: `macOS-26.4-arm64-arm-64bit`
GitHub SHA: `982da71f6c5599ffabfa89650b19d01bd552d28e`
Model file GiB: `4.7108`
Load seconds: `37.5377`
Peak RSS GiB: `1.951`
Min available GiB: `0.6105`
Peak swap GiB: `1.6871`

## Cases
| Case | Prompt tokens | Max tokens | Repeat | Status | Seconds | tok/s | Output tokens |
|---|---:|---:|---:|---|---:|---:|---:|
| warmup_1tok | 2 | 1 | 1 | passed | 28.3886 | 0.0352 | 1 |
| tiny_2tok | 2 | 2 | 1 | passed | 11.8624 | 0.1686 | 2 |
| tiny_2tok | 2 | 2 | 2 | passed | 1.96 | 1.0204 | 2 |
| short_8tok | 11 | 8 | 1 | passed | 6.6425 | 1.2044 | 8 |
| medium_prefill_1tok | 30 | 1 | 1 | passed | 1.8534 | 0.5396 | 1 |
