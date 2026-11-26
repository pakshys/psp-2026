# Backend

## Structure

The backend follows the structure provided in the architecture document:

```
backend/
├── AuctionHub.sln
├── src/
│   ├── AuctionHub.Api/             — Controllers and SSE endpoints
│   ├── AuctionHub.Application/     — Use-case services and interfaces
│   ├── AuctionHub.Domain/          — Business entities and business rules
│   ├── AuctionHub.Infrastructure/  — DB, storage, external integrations
│   └── AuctionHub.Worker/          — Background processes
└── tests/
    ├── AuctionHub.Application.Tests/
    ├── AuctionHub.Domain.Tests/
    └── AuctionHub.IntegrationTests/
```