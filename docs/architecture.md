# Architecture

A private Java Edition survival server owns world state. An agent harness maps model decisions to Minecraft actions and collects local observations. Agents have individual memory and can coordinate through in-game chat and shared records. Store credentials outside the repository.

Use a server-side component to record each death and persist its respawn eligibility timestamp by player UUID before allowing another spawn. Block world interaction until eligibility and restore pending cooldowns on startup. Log deaths, reconnects and respawns with run IDs and UTC timestamps.
