# Qwopus3.5 vs Qwen3.5 9B 4-bit MLX benchmark

Status: `started`
Started: `2026-05-30T04:43:28Z`
Updated: `2026-05-30T04:43:28Z`
Runner: `GitHub Actions 1000004790 macOS ARM64`
Platform: `macOS-26.4-arm64-arm-64bit`
GitHub SHA: `41903cea622c9a491d92203a62c0e883ebd13a09`
Peak RSS GiB: `0.0458`
Min available GiB: `3.0968`
Peak swap GiB: `0.0`

## Models
| Label | Model ID | Status | File GiB | Load seconds | Best tok/s | Avg tok/s |
|---|---|---|---:|---:|---:|---:|
| qwopus3.5_9b_4bit_mlx | `Jackrong/MLX-Qwopus3.5-9B-v3-4bit` | started | 4.7108 | None | None | None |

## Cases
| Model | Case | Prompt tokens | Max tokens | Repeat | Status | Seconds | tok/s | Output tokens |
|---|---|---:|---:|---:|---|---:|---:|---:|

## Baseline resolution
```json
{
  "baseline_id": "mlx-community/Qwen3.5-9B-4bit",
  "method": "candidate_id",
  "details": [
    {
      "model_id": "Jackrong/MLX-Qwen3.5-9B-v3-4bit",
      "error": "RepositoryNotFoundError('401 Client Error. (Request ID: Root=1-6a1a6af0-429def4b055a2ad87693b55f;3d08c41a-294a-4ebc-ad04-70c7278c18ee)\\n\\nRepository Not Found for url: https://huggingface.co/api/models/Jackrong/MLX-Qwen3.5-9B-v3-4bit?blobs=true.\\nPlease make sure you specified the correct `repo_id` and `repo_type`.\\nIf you are trying to access a private or gated repo, make sure you are authenticated and your token has the required permissions.\\nFor more details, see https://huggingface.co/docs/huggingface_hub/authentication\\nInvalid username or password.')"
    },
    {
      "model_id": "Jackrong/MLX-Qwen3.5-9B-4bit",
      "error": "RepositoryNotFoundError('401 Client Error. (Request ID: Root=1-6a1a6af0-5d31eb8e3e515db02bc0c51d;dd488877-e718-4b48-a80d-c87e6c26dd5b)\\n\\nRepository Not Found for url: https://huggingface.co/api/models/Jackrong/MLX-Qwen3.5-9B-4bit?blobs=true.\\nPlease make sure you specified the correct `repo_id` and `repo_type`.\\nIf you are trying to access a private or gated repo, make sure you are authenticated and your token has the required permissions.\\nFor more details, see https://huggingface.co/docs/huggingface_hub/authentication\\nInvalid username or password.')"
    }
  ]
}
```
