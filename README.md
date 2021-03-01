# TokiBot

TokiBot is still work in work in progress and has many bugs!

# ToDo

- [ ] Add Discord server backups
- [ ] Add server status embeds!
- [ ] All moderation commands
- [ ] Add music commands
- [ ] Add Levelling system
- [ ] Add economy system
- [ ] Switch to mongodb
- [x] Add a better help command
- [x] Add command handler

# Installation guide
If you do not know how to host a bot or have no knowledge in javascript then please do some research before installing this!

- First please make sure that you have nodejs 14 installed on your server. If you do not have it installed you can install it from https://nodejs.org/en/ 

- Download all the dependencies using `npm i`

- After you have installed all dependencies you need to put your token in config.json. 

- TokiBot is now ready to run!

# How to add your own commands
To add your own commands you just need to follow this template:
```js
module.exports = {
	name: 'example',
        description: 'This is an example!',
        usage: '-example',
        inHelp: 'yes',
        async run(client, message, args) {
		//code goes here!
	},
};
```
