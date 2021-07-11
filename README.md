Docker-compose abstraction of the [isso](https://github.com/posativ/isso) comment server.   
## Installation
1. Clone the repo
1. Load the isso submodule with:   
   `git submodule update --init`
1. Copy and rename `config/isso.cfg.dist` to `config/isso.cfg`
1. Adjust config file to your specific needs referring to the official [documentation](https://posativ.org/isso/docs/configuration/server/)
1. Run the project:
   `docker-compose up -d`
1. Test your installation by going to `<prefix>/js/embed.min.js`
1. Configure the client-side widget referring to the official [documentation](https://posativ.org/isso/docs/configuration/client/)

