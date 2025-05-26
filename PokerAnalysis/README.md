# PokerAnalysis

A comprehensive poker hand analysis and training platform built with .NET 8, Blazor, and modern enterprise patterns.

## Getting Started

1. Clone the repository.
2. Run `docker-compose up` to start SQL Server and Redis.
3. Open the solution in Rider.
4. Update connection strings in `appsettings.Development.json` if needed.
5. Build and run the solution.

## Project Structure

- `PokerAnalysis.Domain` - Business entities and rules
- `PokerAnalysis.Application` - Use cases and business logic
- `PokerAnalysis.Infrastructure` - Data access and external services
- `PokerAnalysis.WebApi` - REST API controllers
- `PokerAnalysis.BlazorApp` - Web UI application
- `PokerAnalysis.BackgroundJobs` - Background processing
- `tests/` - Unit, integration, and load tests

## Docker Services

- **SQL Server**: localhost:1433
- **Redis**: localhost:6379