# executable
Scripts to execute directly in the CLI.

## Follow the steps to use the excute the scripts.

- step 1 -> Get the raw link 
     - Open script file you wanna excute.
     - Click the ```RAW``` option in the top right in the file view in github.
     - Copy the URL 
     - **Example** : ```https://raw.githubusercontent.com/hari1119/executable/main/bash/docker-setup```
- setp 2 -> Excute command in CLI.
     - use the program type to excute the link directly.
     - ```bash <(curl -s <github-url>) <options-based-on-the-script>```
     - **Example** : ``` bash <(curl -s https://raw.githubusercontent.com/hari1119/executable/main/bash/docker-setup) -h ```
