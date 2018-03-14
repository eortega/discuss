# Discuss

To start this Phoenix (Dockerized, you must have installed Docker) app:

  * Only on the first run, build Phoenix 1.2.5 Image `./build.sh`
  * Start Phoenix with `docker-compose up`
  * Install dependencies with `./mix deps.get`
  * Create and migrate your database with `./mix ecto.create && ./mix ecto.migrate`
  * Install Node.js dependencies with `./run npm install`


Now you can visit [`localhost:4001`](http://localhost:4001) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Common tasks
  * Create a Migration File `./mix ecto.gen.migration name_of_migration`
  * Execute a Migration `./mix ecto.migrate`
