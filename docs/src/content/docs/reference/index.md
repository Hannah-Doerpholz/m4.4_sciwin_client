--- 
title: Workflow creation examples
---

# Reference
SciWIn client provides commands for project initialization ([`s4n init`](init.md)), working with CWL CommandLineTools ([`s4n tool`](tool.md)) and CWL Workflows ([`s4n workflow`](workflow.md)), metadata annotation ([`s4n annotate`](annotate.md)), the execution of CWL ([`s4n execute`](execute.md)) and synchronization with a remote sever ([`s4n sync`](sync.md)).

!!! abstract "Usage"
    ```
     _____        _  _    _  _____         _____  _  _               _   
    /  ___|      (_)| |  | ||_   _|       /  __ \| |(_)             | |   
    \ `--.   ___  _ | |  | |  | |  _ __   | /  \/| | _   ___  _ __  | |_  
     `--. \ / __|| || |/\| |  | | | '_ \  | |    | || | / _ \| '_ \ | __|
    /\__/ /| (__ | |\  /\  / _| |_| | | | | \__/\| || ||  __/| | | || |_  
    \____/  \___||_| \/  \/  \___/|_| |_|  \____/|_||_| \___||_| |_| \__|
    
    Client tool for Scientific Workflow Infrastructure (SciWIn)
    Documentation: https://fairagro.github.io/m4.4_sciwin_client/
    
    Version: 0.5.2
    
    Usage: s4n <COMMAND>
    
    Commands:
      init         Initializes project folder structure and repository
      tool         Provides commands to create and work with CWL CommandLineTools
      workflow     Provides commands to create and work with CWL Workflows
      annotate     Annotate CWL files
      execute      Execution of CWL Files locally or on remote servers [aliases: ex]
      sync         
      completions  Generate shell completions
      help         Print this message or the help of the given subcommand(s)
    
    Options:
      -h, --help     Print help
      -V, --version  Print version
    ```

## Shell completions
Shell completions are available using the `s4n completions` command
!!! abstract "Usage"
    ``` 
    Generate shell completions

    Usage: s4n completions <SHELL>

    Arguments:
      <SHELL>  [possible values: bash, elvish, fish, powershell, zsh]

    Options:
      -h, --help  Print help
    ```
The command can be used to generate the shell completions for several shells.
```
s4n completions bash > completions.sh
```
