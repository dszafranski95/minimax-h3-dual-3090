This machine uses the MiniMax H3 Dual RTX 3090 Runtime.

Before changing, launching, tuning or using MiniMax H3:

1. Read README.md in the MiniMax H3 runtime repository.
2. Read configs/minimax_h3_2x3090_MASTER_WORKFLOW.json in full.
3. Treat the master JSON as the persistent source of truth for this machine unless I explicitly override a setting.
4. Validate the current environment against the profile before applying changes.
5. Prefer the documented production profile over experimental optimizations.
6. Never stack acceleration methods that the profile explicitly warns against.
7. Keep both RTX 3090 GPUs enabled for the multi-GPU H3 workflow.
8. Use the stock VAE decode path on this 24 GB-per-GPU setup unless the profile is intentionally changed.

Acknowledge with:
MINIMAX-H3: runtime loaded · dual RTX 3090 profile
