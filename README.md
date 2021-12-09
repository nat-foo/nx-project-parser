# nx-project-parser
When generating workspaces in NX, the default option will add the workspaces's configuration data to the root `workspace.json`. Sometimes you don't realise you actually want everything stored in its own `project.json` file until you've already got hundreds of libraries using `workspace.json`. This script crawls through your NX monorepo and fixes exactly that problem.
