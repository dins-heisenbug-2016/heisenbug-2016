### Overview

A presentation for http://heisenbug.ru/talks/full-cycle-testing-of-dockerized-microservices/

### Quick Start

0. First we clone the project to a directory, and `cd` to the root directory.

   ```bash
   git clone https://github.com/dins-heisenbug-2016/presentation.git
   cd presentation
   ```

0. Install dependencies. It may take a while to install all the dependencies, please be patient :D

    ```bash
    npm install
    ```
0. Edit the `var/config.coffee` file if needed. Change the value of the `token`, this is the password for logging in as host.

0. Now you can have a cup of tea, and start the test server.

    ```bash
    npm test
    ```

0. Visit the `http://127.0.0.1:8013` in browser, the server should work.
