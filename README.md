# Repo Updater

A minimalist tool to update dependencies in multiple React apps locally.

## Installation

You can run this tool directly using npx:

```bash
npx github:zatteo/repo-updater
```

Or install it globally:

```bash
npm install -g github:zatteo/repo-updater
repo-updater
```

## Usage

This tool works only if you have the following tree:

```
root-app-folder
├── app1
├── app2
├── app3
```

1. Navigate to the `root-app-folder`
2. Run the tool
3. Follow the interactive prompts

⚠️ This tool modify your git history 
⚠️ You must not have WIP work in your apps

<img width="857" height="191" alt="Screenshot 2026-02-25 at 17 24 46" src="https://github.com/user-attachments/assets/521dbe85-f3dc-4d0d-a183-63506b1c29b4" />

## License

MIT
