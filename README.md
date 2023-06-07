# Minishell (Almost as beautiful as shell)

Minishell is a 42 school project. 

The main goal of this project is to simulate bash shell.

## Usage

```bash
make
./minishell
```

## But what is implemented?
Minishell can be used to run bash commands (with or without pipe ```|```)

It can handle redirections such as ```<```  ```>```  ```<<```  ```>>```

Some commands are implemented by us: ```cd, pwd, echo (with -n flag), env, export, unset```

It can also handle ctrl+c and ctrl+d keyboard input to interrupt and exit processes

It also has expansion feature such as echo ```$USER``` that will print ```/yarutiun``` or anything that can be expanded from env

It can expand echo ```$?``` and print the last exit code.

You can navigate through your last input using arrows Up and Down
