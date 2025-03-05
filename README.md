URSYS MIN (`ursys-min`) is a minimal version of [URSYS](https://github.com/dsriseah/ursys), a javascript framework for developing learning sciences web applications.
This package is designed to interoperate with legacy apps that do not support ESM or Typescript.

## Tested Requirements

- MacOS with XCode Command Line Tools installed
- Linux Ubuntu
- NodeJS version 18 and above

## Installation

#### 1. Clone the Repo to Legacy Project
```
cd <root_directory_of_legacy_>
git clone https://github.com/dsriseah/ursys-min.git _mur
```

#### 2. Configure Legacy Project

1. Add `_mur` to your project's `.gitignore`
2. Copy the `_install/@build-ursys-min.sh` shell script to project root
3. To your build scripts, add the call to `@build-ursys-min.sh` shell script (copied in previous step)

#### 3. (Optional) Typescript Intellisense for Visual Studio Code

For reliable live linting of Typescript in VSCODE, your project workspace needs a `tsconfig.json` in the project workpace root. 

- If you **don't** have a `tsconfig.json` in your project root, you can copy the `tsconfig` and `tsconfig-mur` files there. 
- If you **already have** a `tsconfig.json` in the project root, you can just copy the `tsconfig-mur.json` file (assuming there is no existing project)

