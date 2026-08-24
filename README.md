# DeShawn's Dog Walking (.NET 10)

This branch is identical to `main` except for the .NET version it targets. Use this branch if your cohort is running .NET 10 instead of .NET 8.

## What's different from `main`
- `DeShawnsDogWalking.csproj`: `TargetFramework` is `net10.0` (was `net8.0`), and `Swashbuckle.AspNetCore` is updated to `10.2.3` (was `6.2.3`) to match.
- `.vscode/launch.json`: the debug `program` path points at `bin/Debug/net10.0/...` (was `net8.0`).

Everything else — `Program.cs`, the client, the setup instructions — is unchanged. Follow the curriculum's setup chapter as normal.

**Add your ERD here**