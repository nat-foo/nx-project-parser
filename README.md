# nx-project-parser
When generating modules in NX, the default option will add the module's configuration data to the workspace.json. Sometimes you don't realise you actually want everything stored in its own project.json file until you've already got hundreds of libraries using workspace.json. This project fixes exactly that problem.
