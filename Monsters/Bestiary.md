```statblock
{
	"name": "Zombie Plague Spreader",
	"layout": "Basic 5e Layout",
	"source": "VRGR",
	"size": [
		"M"
	],
	"type": "undead",
	"ac": [
		10
	],
	"hp": {
		"average": 78,
		"formula": "12d8 + 24"
	},
	"speed": {
		"walk": 30
	},
	"str": 16,
	"dex": 10,
	"con": 15,
	"int": 3,
	"wis": 5,
	"cha": 5,
	"senses": [
		"darkvision 60 ft."
	],
	"passive": 7,
	"resist": [
		"necrotic"
	],
	"immune": [
		"poison"
	],
	"conditionImmune": [
		"charmed",
		"exhaustion",
		"poisoned"
	],
	"languages": [
		"understands the languages it knew in life but can't speak"
	],
	"cr": "4",
	"trait": [
		{
			"name": "Undead Fortitude",
			"entries": [
				"If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead."
			]
		},
		{
			"name": "Unusual Nature",
			"entries": [
				"The zombie doesn't require air, food, drink, or sleep."
			]
		},
		{
			"name": "Viral Aura",
			"entries": [
				"Any creature that starts its turn within 10 feet of the plague spreader must make a {@dc 12} Constitution saving throw. On a failed save, the creature is {@condition poisoned} and can't regain hit points until the end of its next turn. On a successful save, the creature is immune to this plague spreader's Viral Aura for 24 hours."
			]
		}
	],
	"action": [
		{
			"name": "Multiattack",
			"entries": [
				"The plague spreader makes two Slam attacks."
			]
		},
		{
			"name": "Slam",
			"entries": [
				"{@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d6 + 3}) bludgeoning damage plus 9 ({@damage 2d8}) necrotic damage."
			]
		},
		{
			"name": "Virulent Miasma (1/Day)",
			"entries": [
				"The plague spreader releases toxic gas in a 30-foot-radius sphere centered on itself. Each creature in that area must make a {@dc 12} Constitution saving throw, taking 14 ({@damage 4d6}) poison damage on a failed save, or half as much damage on a successful one. A Humanoid reduced to 0 hit points by this damage dies and rises as a zombie (see its stat block in the Monster Manual) 1 minute later. The zombie acts immediately after the plague spreader in the initiative count."
			]
		}
	],
	"traitTags": [
		"Undead Fortitude",
		"Unusual Nature"
	],
	"senseTags": [
		"D"
	],
	"actionTags": [
		"Multiattack"
	],
	"languageTags": [
		"CS",
		"LF"
	],
	"damageTags": [
		"B",
		"I",
		"N"
	],
	"miscTags": [
		"AOE",
		"MW"
	],
	"conditionInflict": [
		"poisoned"
	],
	"savingThrowForced": [
		"constitution"
	],
	"hasToken": true,
	"hasFluff": true
}
```
