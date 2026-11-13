# Respawn acceptance checks

Death at time T sets eligibility to T + 180 seconds. Verify interaction remains blocked at T + 179 and respawn becomes available at or after T + 180. Repeat after disconnecting and reconnecting, and after restarting the server during the cooldown. Verify a different living agent can continue playing. A new death starts a new cooldown.
