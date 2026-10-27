[README.md](https://github.com/user-attachments/files/34035463/README.md)

## Project 1 — ServiceDesk Hub
- ASP.NET Core 8 minimal API, EF Core, SQLite (easy local setup), React, TypeScript, Vite
- Request creation, listing, filtering, status updates, deletion endpoint, validation, seeded synthetic records
- Responsive operations dashboard with labeled controls and accessible error feedback

### Run
1. Install .NET 8 SDK and Node.js 20+.
2. In `servicedesk-hub-api`, run `dotnet restore` then `dotnet run --urls http://localhost:5000`.
3. In a separate terminal, in `servicedesk-hub-ui`, run `npm install` then `npm run dev`.
4. Open `http://localhost:5173`.

### API routes
`GET /api/requests`, `GET /api/requests/{id}`, `POST /api/requests`, `PATCH /api/requests/{id}/status`, `DELETE /api/requests/{id}`.

Example POST JSON: `{ "applicantName": "Taylor Smith", "program": "Housing Assistance" }`.

