1. **Using Corepack**  
   Corepack comes pre-installed with Node.js versions 16.13+ and allows you to install package managers like pnpm.

   - **macOS and Windows**:  
     Enable Corepack and install pnpm:
     ```bash
     corepack enable
     corepack prepare pnpm@latest --activate
     ```

2. **Using npm (Node Package Manager)**  
   If you already have `npm` installed, you can use it to install `pnpm` globally.

   - **macOS and Windows**:
     ```bash
     npm install -g pnpm
     ```

3. **Using Homebrew (macOS)**  
   Homebrew can be used to install `pnpm` directly.

   - **macOS**:
     ```bash
     brew install pnpm
     ```

4. **Using Scoop or Chocolatey (Windows)**

   - **Scoop (Windows)**:  
     Install Scoop first if you don't have it:

     ```bash
     Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
     iwr -useb get.scoop.sh | iex
     ```

     Then install `pnpm` using Scoop:

     ```bash
     scoop install pnpm
     ```

   - **Chocolatey (Windows)**:  
     Install `pnpm` using Chocolatey:
     ```bash
     choco install pnpm
     ```

5. **Using Shell Script**  
   `pnpm` provides a shell script to install the package manager. This method works for both macOS and Windows (via Git Bash or WSL).

   - **macOS and Windows**:
     ```bash
     curl -fsSL https://get.pnpm.io/install.sh | sh -
     ```

6. **Using Volta**  
   Volta is a version manager for JavaScript tools that allows you to easily install `pnpm`.

   - **macOS and Windows**:  
     Install Volta first:
     ```bash
     curl https://get.volta.sh | bash
     ```
     Then install `pnpm` using Volta:
     ```bash
     volta install pnpm
     ```
