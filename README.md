# GDGADK-March16
 @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        multi_tool_agent/
        requirements.txt

nothing added to commit but untracked files present (use "git add" to track)
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ git add --all
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   multi_tool_agent/.adk/session.db
        new file:   multi_tool_agent/.env
        new file:   multi_tool_agent/__init__.py
        new file:   multi_tool_agent/agent.py
        new file:   requirements.txt

(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ git commit -m "https://google.github.io/adk-docs/get-started/quickstart/"
[main 6ad4ff6] https://google.github.io/adk-docs/get-started/quickstart/
 6 files changed, 97 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 multi_tool_agent/.adk/session.db
 create mode 100644 multi_tool_agent/.env
 create mode 100644 multi_tool_agent/__init__.py
 create mode 100644 multi_tool_agent/agent.py
 create mode 100644 requirements.txt
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ ls -al
total 36
drwxrwxrwx+ 6 codespace root      4096 Mar 17 03:07 .
drwxr-xrwx+ 5 codespace root      4096 Mar 17 02:09 ..
drwxrwxrwx+ 3 codespace codespace 4096 Mar 17 03:07 .adk
drwxrwxrwx+ 8 codespace root      4096 Mar 17 03:37 .git
-rw-rw-rw-  1 codespace codespace  265 Mar 17 02:38 .gitignore
drwxrwxrwx+ 5 codespace codespace 4096 Mar 17 02:25 .venv
-rw-rw-rw-  1 codespace root        16 Mar 17 02:09 README.md
drwxrwxrwx+ 4 codespace codespace 4096 Mar 17 03:11 multi_tool_agent
-rw-rw-rw-  1 codespace codespace   10 Mar 17 02:27 requirements.txt
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16 (main) $ cd mu*
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16/multi_tool_agent (main) $ ls -al
total 28
drwxrwxrwx+ 4 codespace codespace 4096 Mar 17 03:11 .
drwxrwxrwx+ 6 codespace root      4096 Mar 17 03:07 ..
drwxrwxrwx+ 2 codespace codespace 4096 Mar 17 03:20 .adk
-rw-rw-rw-  1 codespace codespace   87 Mar 17 03:13 .env
-rw-rw-rw-  1 codespace codespace   20 Mar 17 02:43 __init__.py
drwxrwxrwx+ 2 codespace codespace 4096 Mar 17 03:15 __pycache__
-rw-rw-rw-  1 codespace codespace 1866 Mar 17 03:18 agent.py
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16/multi_tool_agent (main) $ cd .adk
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16/multi_tool_agent/.adk (main) $ ls -al
total 68
drwxrwxrwx+ 2 codespace codespace  4096 Mar 17 03:20 .
drwxrwxrwx+ 4 codespace codespace  4096 Mar 17 03:11 ..
-rw-r--r--  1 codespace codespace 57344 Mar 17 03:20 session.db
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16/multi_tool_agent/.adk (main) $ git push

To https://github.com/SumatiNat/GDGADK-March16
   59f4c6c..6ad4ff6  main -> main
(.venv) @SumatiNat ➜ /workspaces/GDGADK-March16/multi_tool_agent/.adk (main) $ 
