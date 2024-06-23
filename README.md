# My Developer Journal

## Configuring tsconfig file to recongize types in node_modules folder

###### If typeRoots in compilerOption was configured:

- Be sure @types/jest dependency can be installed with current node version that is being used in the terminal
- If typeRoots compilerOption was configured, the /node_modules folder must also be pointed in. By default, typeRoots points to the /node_modules folder, but when typeRoots is configured, it no longer will point to the /node_modules folder

