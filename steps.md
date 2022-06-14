# Linux Installation

1. Install dependencies
   
   ```
   sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev
   ```

2. Install .pyenv

    ```
    curl https://pyenv.run | bash
    ```

3. Add .pyenv to .bashrc

    ```
    export PATH="$HOME/.pyenv/bin:$PATH"
    eval "$(pyenv init --path)"
    eval "$(pyenv virtualenv-init -)"
    ```