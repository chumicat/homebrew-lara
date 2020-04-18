# Some Title
## Some Description
## Command List
```shell
# ===== LARA DEVLOPER COMMAND ===== #
lara db:create                # Locally, CREATE table t0 in lara.db
lara db:select                # Locally, SELECT value with key in t0
lara db:insert                # Locally, INSERT item(key-value) in t0
lara db:delete                # Locally, DELETE item with key in t0
lara db:update                # Locally, UPDATE item with key in t0
lara db:mix                   # Locally, SELECT/INSERT/UPDATE on situation, use as set
lara db:++                    # Locally, Increase value with key in t0
lara db:global                # Globally, SELECT global data, read only
lara lara:release             # Generate README.md
lara lara:release             # Do trivia and release lara
# ===== LARA GENERAL COMMAND ===== #
lara list                     # List all command
lara status                   # Check HEAD
lara version                  # Show script version
lara setenv                   # Check and Set environment
# ===== PROJECT CONTROL COMMAND ===== #
lara new <domain> [-dg]       # New a laravel project
lara init <domain> [-d]       # Initial a laravelproject after clone
lara switch <domain>          # Switch HEAD to project
lara release <domain>         # Generate initial script to project
# ===== IN PROJECT COMMAND (OUT DOCKER) ===== #
lara up [-der]                # Up HEAD project
lara down                     # down HEAD project
lara restart                  # restart HEAD project
lara downup [-der]            # downup HEAD project
lara enter [-r]               # enter HEAD project workspace
lara site                     # open HEAD project site and document
lara site api                 # open HEAD project swagger API document
# ===== IN PROJECT COMMAND (IN DOCKER) ===== #
lara require ...              # require package to HEAD project
lara require swagger
lara require npm|sasslara
lara require *                # general command as run in HEAD project
# ===== HADN"T DEAL ===== #

```