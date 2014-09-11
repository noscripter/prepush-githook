# prepush-githook ![prepush-githook](https://david-dm.org/mytcer/prepush-githook.png)&nbsp;![prepush-githook version](https://badge.fury.io/js/prepush-githook.svg)&nbsp;![prepush-githook donwloads](http://img.shields.io/npm/dm/prepush-githook.svg)

![prepush-githook](https://nodei.co/npm/prepush-githook.png?stars&downloads)

> Introduction：An npm installable git pre-push hook used to lint and test your code

<br>

### Installation

	npm install githook-prepush --save-dev

<br>

### Usage

Config `scripts` and `prepush` fields in your project's `package.json`：

	{
		"scripts": {
			"lint": "your lint command",
			"test": "your test command",
			"xxx": "your xxx command"
		},
		"prepush": ["lint", "test", "xxx"]
	}

	note：you can customize the script name（xxx），then to do any thing you want.

	




