1. Clone this repo: https://github.com/shrutishrestha/testing-github-actions
   
2. Go inside your repo and run ./run.sh. You will see the runner in idle state under settings > Actions > Runners
(base) sshrestha8@arclogin04:~/testing-github-actions/actions-runner$ ./run.sh

3. Now, when you will edit and commit the random_test_file.py file then this will execute the below workflow.
https://github.com/shrutishrestha/testing-github-actions/blob/main/.github/workflows/try_runner.yaml

4. Then, you can see success under action for the latest run.

