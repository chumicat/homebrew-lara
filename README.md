# Some Title
## Some Description
## Command List
```shell
# ===== LARA DEVLOPER COMMAND ===== #
lara db:create                # Locally, CREATE table t0 in lara.db
lara db:list                  # Locally, list all items in t0
lara db:where                 # Locally, return value matched key in t0
lara db:insert                # Locally, INSERT item(key-value) in t0
lara db:delete                # Locally, DELETE item with key in t0
lara db:update                # Locally, UPDATE item with key in t0
lara db:mix                   # Locally, INSERT/DELETE/UPDATE on situation, use as set
lara db:                      # Locally, Do operation on value with key in t0
lara db:global                # Globally, SELECT global data, read only
lara dev:readme               # Generate README.md
lara dev:release              # Do trivia and release lara

# ===== LARA ENVIRONMENT COMMAND ===== #
lara lara:setenv              # Check and Set environment
lara lara:setdir              # Set lara working directory for all laravel peoject
lara lara:unsetdir            # Remove laradock and db of lara working directory 

# ===== LARA GENERAL COMMAND ===== #
lara list                     # List all command
lara domain:lara              # List all domain
lara status                   # Check HEAD
lara version                  # Show script version

# ===== PROJECT CONTROL COMMAND ===== #
lara new <domain> [-dg]       # New a laravel project
lara switch <domain>          # Switch HEAD to project
lara release <domain>         # Generate initial script to project

# ===== IN PROJECT COMMAND (OUT DOCKER) ===== #
lara init [-d]                # Initial a laravelproject after clone
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
lara require npm|sass         
lara require *                # general command as run in HEAD project
# ===== HADN"T DEAL ===== #

```