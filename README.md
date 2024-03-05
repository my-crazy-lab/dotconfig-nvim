This is my .config/nvim in MacOs or Linux.

## Setup environments 
1. lua-language-server
    * macos: brew install lua-language-server
    * ubuntu: <br>
        sudo apt update <br>
        sudo apt install lua5.4 <br>
        cd <br>
        git clone https://github.com/sumneko/lua-language-server <br>
        git submodule update --init --recursive <br>
        cd 3rd/luamake <br>
        compile/install.sh <br>
        cd lua-language-server <br>
        cd ../.. <br>
        ./3rd/luamake/luamake rebuild <br>
        echo 'export PATH="$HOME/lua-language-server/bin:$PATH"' >> ~/.zshrc
        source ~/.zshrc
2.      
