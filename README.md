# JAVASCRIPTING

> Learn JavaScript by adventuring around in the terminal.  

> _Looking for more interactive tutorials like this? Go to [nodeschool.io](http://nodeschool.io)._

## Get help
Having issues with javascripting? Get help troubleshooting in the [nodeschool discussions repo](http://github.com/nodeschool/discussions), or on gitter:

[![Gitter](https://img.shields.io/gitter/room/gitterHQ/gitter.svg)](https://gitter.im/nodeschool/discussions?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Install Node.js

Make sure Node.js is installed on your computer.

Install it from [nodejs.org](https://nodejs.org/)

On Windows and using v4 or v5 of Node.js? Make sure you are using at least 5.1.0, which provides a fix for a bug on Windows where you can't choose items in the menu.

### Install `javascripting` with `npm`

Open your terminal and run this command:

```
npm install --global javascripting
```

The `--global` option installs this module globally so that you can run it as a command in your terminal.

#### Having issues with installation?

If you get an `EACCESS` error, the simplest way to fix this is to rerun the command, in either of the following ways:

- On unix shells, prefix the command with sudo
> `sudo npm install --global javascripting`

- On Windows and if using either PowerShell or CMD, ensure you open the shell with administrator privilege.

You can also fix the permissions so that you don't have to use `sudo`. Take a look at this npm documentation:
https://docs.npmjs.com/getting-started/fixing-npm-permissions

## Run the workshop

Open your terminal and run the following command:

```
javascripting
```

You'll see the menu:

![javascripting screenshot](screenshot.png)

Navigate the menu with the up & down arrow keys. 

Choose a challenge by hitting enter.

### Take a look at this gif that shows the first challenge:

![first challenge](javascripting.gif)

In the gif I'm using the command line editor `nano` ([here are some basic usage tips for nano](https://github.com/sethvincent/dev-envs-book/blob/master/chapters/05-editors.md#nano)).  

You can use any editor you like. 

[atom](http://atom.io) or [brackets](http://brackets.io/) are both good options.

## Need help with an exercise?

Open an issue in the nodeschool/discussions repo: https://github.com/nodeschool/discussions

Include the name `javascripting` and the name of the challenge you're working on in the title of the issue.

## Get Involved

Code contributions welcome! Please check our [documentation on contributing](https://github.com/workshopper/javascripting/blob/master/CONTRIBUTING.md) to get started.

## TODOS:

Add these challenges:

- "FUNCTION RETURN VALUES"
- "THIS"

## License

MIT
