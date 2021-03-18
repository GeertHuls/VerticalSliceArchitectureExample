# Clean architecture example

Run 'docker-compose up' first to spin up the database.

## EF migrations

Open package manager console and select project *GloboTicket.TicketManagement.Persistence*.
> add-migration InitialMigration

Run the migrations.
> update-database
