# meru.import.artifacts

Work with library:
1. Clone two repositories to the same folder on your device:
   `https://github.com/lsnova/meru-import-model` (java model repository)
   `https://github.com/lsnova/meru.import.artifacts` (library artifacts repository)
2. Add your local changes in `meru-import-model` project.
3. In `meru-import-model` project directory run command: ``mvn clean deploy -P snapshot``
4. After successful command execution you will see changes in `meru.import.artifacts` project.
5. Changes in both projects has to be committed and pushed to repositories.
