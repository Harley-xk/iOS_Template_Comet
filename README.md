# iOS Project Template Comet

## Introduction

This is an iOS Project Template for Cookiecutter.

## Usage

You can simply create project with this template with following steps.

*For more infomation about Cookiecutter, you can refer to the [Documents](https://cookiecutter.readthedocs.io/en/latest/) or read [This](https://www.jianshu.com/p/a404ab38dac2) Simplyfied Chinese article.*

### Install Cookiecutter

Simply install Cookiecutter on macOS with homebrew:

```bash
brew install cookiecutter
```

### Create Project

cd into your project directory and create project with this template:

```bash
cookiecutter https://github.com/Harley-xk/iOS_Template_Comet.git
```

enter your project name an other names:

```bash
product_name [Hello]: MyApp
organization_name [Someone Co.,Ltd.]: My Company Co.,Ltd.
bundle_identifier [com.someone.app]: com.mycompany.myapp
```

After all pods are successfully installed, the new priject will be opened by Xcode automatically.