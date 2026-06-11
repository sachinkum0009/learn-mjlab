# Learn MjLab

```bash
uv sync

uv run list-envs

uv run train My-Cartpole-Swingup --env.scene.num-envs 4096

uv run play My-Cartpole-Swingup --checkpoint-file model_499.pt

uv run play My-Cartpole-Swingup --wandb-run-path <username,project,id>

uv run play My-Cartpole-Swingup --checkpoint-file model_499.pt --viewer viser
```
