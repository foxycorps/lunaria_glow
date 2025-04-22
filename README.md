# Lunaria Glow

A dark Visual Studio Code theme with a soft pastel palette.

## Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/foxycorps/lunaria_glow
   cd lunaria_glow
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

3. Launch VS Code in development mode:
   ```bash
   code --extensionDevelopmentPath=$(pwd)
   ```

4. In VS Code, go to the debug panel and run "Launch Extension".

## Publishing

1. Install `vsce` if you haven't:
   ```bash
   npm install -g vsce
   ```
2. Login to your publisher:
   ```bash
   vsce login foxycorps
   ```
3. Publish:
   ```bash
   vsce publish
   ```
