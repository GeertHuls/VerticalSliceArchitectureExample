# Clean architecture example

Run 'docker-compose up' first to spin up the database.

## EF migrations

Open package manager console and select project *GloboTicket.TicketManagement.Api*.

Run the migrations.
> update-database -Context GloboTicketDbContext

> update-database -Context GloboTicketIdentityDbContext

Afterwards, run the application, register a user and login with that user.
