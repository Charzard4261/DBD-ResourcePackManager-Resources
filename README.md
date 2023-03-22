# DBD-ResourcePackManager-Resources
This is the Resources for [the DBD Resource Pack Manager](https://github.com/Charzard4261/DBD-ResourcePackManager). It contains json files with information about all of the Survivors and Killers, their perks (and eventually their addons). Feel free to use them for any purpose!

## Contributing
When new characters get introduced into the game, they should be added to json for their side.
Keep in mind that files may be spelt incorrectly or have different names entirely than they have in game, so double check them. If files are in sub folders, those folders should be included in the file path information.
Image links need to be direct, so when using wiki images it needs to be static.wikia link.
### Survivor
Image guide coming soon.
```
"<firstname>_<surname>": {
	"portrait": "<dlc folder/><name>_charSelect_portrait.png",
	"defaultPortrait": "<image link>",
	"perkA": {
		"filePath": "<dlc folder/>iconPerks_<name>.png",
		"defaultImage": "<image link>"
	},
	"perkB": {
		"filePath": "<dlc folder/>iconPerks_<name>.png",
		"defaultImage": "<image link>"
	},
	"perkC": {
		"filePath": "<dlc folder/>iconPerks_<name>.png",
		"defaultImage": "<image link>"
	}
}
```

### Killers
Image guide coming soon.
```
"the_<killer>": {
	"portrait": "<dlc folder/><name>_charSelect_portrait.png",
	"defaultPortrait": "<image link>",
	"powers": [
		"<dlc folder/>iconPowers_<power 1 name>.png",
		"<dlc folder/>iconPowers_<power 2 name>.png",
    ...
	],
	"defaultPower": "<image link>",
	"perkA": {
		"filePath": "<dlc folder/>iconPerks_<name>.png",
		"defaultImage": "<image link>"
	},
	"perkB": {
		"filePath": "<dlc folder/>iconPerks_<name>.png",
		"defaultImage": "<image link>"
	},
	"perkC": {
		"filePath": "<dlc folder/>iconPerks_<name>.png",
		"defaultImage": "<image link>"
	},
	"addons": [ TODO ]
}
```
