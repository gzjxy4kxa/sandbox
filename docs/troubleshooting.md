# Troubleshooting

Common issues when running scripts in this sandbox.

- **Port already in use**: Check with `lsof -i :8080` and kill the process.
- **Permission denied**: Ensure scripts are executable (`chmod +x`).
- **Missing env vars**: Copy `.env.example` to `.env` and fill required values.

For anything else, open an issue.
