# 100 - Add a Dockerfile

Start your action by creating a Dockerfile

Our action will use a Docker container so it will require a `Dockerfile`. Let's add it now. We won't discuss what each line means in detail, but the important thing to know is that the action will be executed in an environment defined by this file.

### :keyboard: Activity: Create a `Dockerfile` and open a pull request

1. Create a file titled `action-a/Dockerfile` by [using this quick link](https://github.com/willem-vanheemstrasystems/hello-github-actions/new/main?filename=action-a/Dockerfile) or manually:
   - Create a new branch. _Branches should be named intentionally, so a good name for this branch could be `first-action`_.
   - On the new branch, create a directory: `action-a`. _Note:_ If you're working on GitHub.com, you can create a directory and a file at the same time by naming the file `action-a/Dockerfile`.
   - In the `action-a` directory, create a file titled `Dockerfile`.
1. Fill the `Dockerfile` with the content below:

   ```Dockerfile
   FROM debian:9.5-slim

   ADD entrypoint.sh /entrypoint.sh
   RUN chmod +x /entrypoint.sh
   ENTRYPOINT ["/entrypoint.sh"]
   ```

2. Commit your file
   - If you're working locally, you will also need stage your file and to push the branch to GitHub.
3. Open a pull request with your new branch against `main`

<hr>

4. Nice work, you committed a `Dockerfile`. You'll notice at the end of the Dockerfile, we refer to an entrypoint script.

```Dockerfile
ENTRYPOINT ["/entrypoint.sh"]
```

The `entrypoint.sh` script will be run in Docker, and it will define what the action is really going to be doing.

