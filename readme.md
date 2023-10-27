1. Quit Docker:
   Close the Docker application if it's running.

2. Navigate to the Docker configuration folder:
   Open your terminal and go to the specified location using the `cd` command:

   ```shell
   cd ~/Library/Group\ Containers/group.com.docker/
   ```

3. Edit the `settings.json` file:
   Use a text editor to open the `settings.json` file. You can use a command-line text editor like `nano` or `vi`, or a graphical text editor like `TextEdit`. Here's an example using `nano`:

   ```shell
   nano settings.json
   ```

4. Change "kubernetesEnabled" to `false`:
   Inside the `settings.json` file, locate the "kubernetesEnabled" key and change its value to `false`, just as you've shown in your provided JSON:

   ```json
   {
     "kubernetesEnabled": false
   }
   ```

5. Save and exit the text editor:
   If you're using `nano`, you can save your changes by pressing `Ctrl + O`, then press `Enter`, and exit by pressing `Ctrl + X`. If you're using another text editor, save the file as you normally would.

6. Reopen Docker:
   Start the Docker application again.

7. Enable Kubernetes:
   Once Docker is running, you should be able to enable Kubernetes from its settings.
