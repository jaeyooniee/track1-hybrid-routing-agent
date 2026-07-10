# LocalFirst

Submission for the AMD Developer Hackathon ACT II, Track 1 (team jae).

LocalFirst is a containerized agent that answers all eight Track 1 task categories while minimizing Fireworks AI token consumption.

## Running it

The agent implements the Track 1 harness contract: it reads `/input/tasks.json`, writes `/output/results.json` as `[{"task_id", "answer"}]`, and exits 0. `FIREWORKS_API_KEY`, `FIREWORKS_BASE_URL`, and `ALLOWED_MODELS` are read from the environment at runtime.

The Docker image is public:

```
ghcr.io/jaeyooniee/track1-hybrid-routing-agent:latest
```
