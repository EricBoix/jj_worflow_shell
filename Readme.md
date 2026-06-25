# A set of shell level utilities when working in jejuneness

## Usage

### Fetch and install the utilities

```bash
git clone https://github.com/EricBoix/jj_workflow_shell.git  # This repository
source jj_worflow_shell/init.bassh 
```

### Configure the shell utilities

- either copying the `env-reference` file of this repository to a new `.env` file
  
  ```bash
  cp jj_worflow_shell/env-reference .env
  ```

- or extend the .env file encountered in the calling directory

  ```bash
  cat jj_worflow_shell/env-reference >> .env
  ```
  
and customize the environment variables values in order to suit your needs.
Note that some variables are only required by some `jj_<command>`.
For example the `LLM_*` variables are only required when using [`jj_extract_knowledge_graph`](./treatments.sh).

### TBD