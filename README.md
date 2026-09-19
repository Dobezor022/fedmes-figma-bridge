# FedMes Figma Remote Bridge

Private relay used by the local FedMes Figma development plugin.

- Put commands in `queue/<jobId>.json`.
- Plugin writes `results/<jobId>.json` and removes the queue file.
- No arbitrary JavaScript is executed. Commands are allowlisted and validated.
- The GitHub token is stored only in Figma `clientStorage`.

Current clientId: `fedmes-mu8avycy-xgfxtpag`
