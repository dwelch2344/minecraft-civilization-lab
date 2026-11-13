# Implementation plan

1. Select compatible Minecraft server and agent harness versions. Pin dependencies and provision the local server.
2. Load the seed configuration and profiles. Validate profile IDs, prompt paths, and the roster.
3. Implement server-side respawn gating and persistent per-agent memory.
4. Record the run manifest and append structured events. Capture initial and final world snapshots.
5. Smoke-test with 3–5 agents, including the death and reconnect checks. Start the ten-agent baseline from a fresh world.
6. Compute evaluation metrics from logs and snapshots and record observations.
