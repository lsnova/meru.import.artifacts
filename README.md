# meru.import.artifacts

## Deploying changes

To deploy changes in this library, follow these steps:

1. **Clone the Repositories:**

   Clone the following two repositories into the same directory on your device:

   - [meru-import-model (Java model repository)](https://github.com/lsnova/meru-import-model)
   - [meru.import.artifacts (library artifacts repository)](https://github.com/lsnova/meru.import.artifacts)

2. **Make Local Changes:**

   Apply your local changes in the `meru-import-model` project.

3. **Deploy the Changes:**

   Run the following script:

   ```sh
   cd ../meru-import-model || exit
   sh update_model.sh
   ```

4. **Commit and Push:**

   Commit changes in both projects are and push to their respective repositories.
