githook-prepush
===============

> Introduction：An npm installable git pre-push hook used to lint and test your code

<br>

### Installation

	npm install githook-prepush --save-dev

<br>

### Usage

	// config "scripts" and "prepush" fields in your project's package.json

	{
		"scripts": {
			"lint": "your lint command",
			"test": "your test command",
			"xxx": "your xxx command"  // note：you can customize "xxx"'s name，to do any thing you want.
		},
		"prepush": ["lint", "test", "xxx"]
	}

	




