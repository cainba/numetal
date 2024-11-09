
# Contributing

####  Start by cloning the repository:

```bash

git clone https://github.com/cainba/numetal.git

```

#### Then cd (change direcotry) to the new directory made by git

```bash

cd numetal

```

#### Since this project is based on the JS runtime Bun make sure you have the latest version of bun installed

>powershell (windows)

```ps

powershell -c "irm bun.sh/install.ps1 | iex"

```

>bash (linux and MacOS)

```bash

curl -fsSL https://bun.sh/install | bash

```

#### After bun is done installing, run the following in the top level directory (root) to install dependencies for the repo

```ts

bun update

```

#### From here you can run the following scripts to start running things. Please look at the wiki for more details

```ts

bun run nu:app:dev //this run a development server, hot reloads on changes
bun run nu:app:watch //this is similar to dev but reloads everything on changes
bun run nu:app:build //compile a buold version of the site to be used in deployments
bun run nu:app:clean //cleans up node_modules and the bun.lockb lock file to get a clean install of the modules

```
