# DotNet Core DevSpaces demo

## Instructions for running in DevSpaces

  1. Navigate to `devspace` directory
  2. Run `devspaces create` command
  3. Once DevSpace is ready, start it using command `devspaces start dotnet-core-demo`
  4. Go back to root of the project `cd ..`
  5. Bind local directory using `devspaces bind dotnet-core-demo` command.
  6. Once the synch is completed. Connect to DevSpace by running `devspaces exec dotnet-core-demo` command.
  7. From your DevSpace run startup script `./start.sh`
