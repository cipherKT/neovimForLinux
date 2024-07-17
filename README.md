Here’s a streamlined step-by-step guide to setting up your Neovim configuration on a new Kali VM using your provided files:

1. **Clone Your Repository:**
   ```sh
   git clone https://github.com/cipherKT/neovimForLinux.git ~/.config/nvim
   ```

2. **Install Neovim:**
   ```sh
   sudo apt update
   sudo apt install neovim
   ```

3. **Install Packer (if not already installed):**
   ```sh
   git clone --depth 1 https://github.com/wbthomason/packer.nvim\
     ~/.local/share/nvim/site/pack/packer/start/packer.nvim
   ```

4. **Install Required Plugins:**
   Open Neovim and run:
   ```vim
   :PackerSync
   ```
5. **Locate teh packer.lua file in lua/r00t3d directory**
   Open it in nvim and run this commands
   ```vim
   :source %
   :PackerSync
   ```
