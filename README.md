# enes680-agent-v2-data

Synthetic test-and-learn data for the ENES 680 Agent v2 demo. All partners, tests, and numbers are fictional.

- `results_index.csv`: index of past A/B tests with links to readout decks
- `readouts/`: one readout per completed test (T-10 deck intentionally missing, T-11 still running)
- `backlog_ideas.csv`: sanitized backlog ideas to run through the agent

The agent fetches `results_index.csv`, picks relevant tests, then opens each `readout_link` at run time.
