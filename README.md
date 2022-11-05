# Librata

An attempt at a CMS.

## Environment

Expectations are that this app will run in a UNIX envrionment.

## Setup

Ensure Postgres and Redis are running and run `bin/setup` to configure the application.

## Run

Run the app with `bin/run`. Optionally, if you have the Heroku CLI installed, run `heroku local`.

Optionally use `LOGRAGE_IN_DEVELOPMENT=true bin/run` to have cleaner production logs in your development environment.

## Testing

Run `bin/ci` for the full test experience. This command runs all tests, Brakeman, and a Bundler audit.