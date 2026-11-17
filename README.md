# ABC Pharmacy — Medicine Tracker

Submission for the .NET coding assessment.

## 📦 Download

The complete project is packaged as **[`PharmacyTracker.zip`](./PharmacyTracker.zip)**.

Click the file above, then click **"Download raw file"** (icon on the top-right of the file view).

## How to run

Once unzipped (`PharmacyTracker/`):

**One-click (Windows)** — double-click `start-app.bat`

**Any OS** — requires .NET SDK 10.0.300+:
```bash
cd PharmacyTracker/server/PharmacyApi
dotnet run
```

Open <http://localhost:5080>.

The pre-built React SPA is bundled, so Node.js is not required to run.

See `HOW_TO_RUN.md` inside the zip for the full guide (dev mode, Docker, tests, troubleshooting).

## Tech stack

- **Backend**: ASP.NET Core 10 Web API
- **Frontend**: React 18 (Vite)
- **Storage**: JSON files on the server (no database)

## Tests

- **Frontend**: 15 Vitest tests — `cd web && npm install && npm test`
- **Backend**: xUnit unit + integration tests — `dotnet test` from the solution root
