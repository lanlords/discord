[![CodeFactor](https://www.codefactor.io/repository/github/lanlords/discord/badge)](https://www.codefactor.io/repository/github/lanlords/discord)
[![Discord Online](https://img.shields.io/discord/351732061561946114.svg)](https://discord.lanlords.nl)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# Lanlords Discord Page

Landing page for Lanlords Discord server. Shows current online users and contains direct Join link.

## Development

For local development you can use Jekyll on the command line and run the build-in development server locally. The easiest way is using Docker Compose. This is a quick way to spin up the Jekyll development environment and a CORS container to fix CORS issues with client-side API calls.

You will only need to have Docker installed. Run the Docker Compose command to start the containers:
```shell
docker-compose up
```
After executing this command you should be able to reach the URL on [http://localhost:4000/](http://localhost:4000/).

## Configuration

Two different configs are used. One for development and one for the production build. You can find them in the root directory:

*   `_config.yml`
*   `_config-dev.yml`

By default the `_config.yml` config is used. During development it's recommend to specify the development `_config-dev.yml` config. The Docker Compose file specifies the development config as well.

## License

[MIT license](LICENSE)
