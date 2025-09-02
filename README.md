# MenuStore
This include allows you to create many types of stores using Textdraws.
![MenuStore](https://i.imgur.com/gH1k6t4.jpg)


### Example code
`
//in your script find cmd:buy and replace with this code
case BUSINESS_STORE:
	    {
			//	s					   ID   model     name              price				  max stack
			MenuStore_AddItem(playerid, 1, 	18874, 	"Mobile Phone",		5000);
			MenuStore_AddItem(playerid, 2, 	330, 	"Portable Radio",	5000);
			MenuStore_AddItem(playerid, 3, 	19625, 	"Cigarette",		50,		"", 0.0, true,	 20);
			MenuStore_AddItem(playerid, 4, 	365, 	"Spraycan", 		1200,		"", 0.0, true,	 20);
			MenuStore_AddItem(playerid, 5, 	1718,	"Phonebook",		600);
			MenuStore_AddItem(playerid, 6, 	367, 	"Camera", 			1500);
			MenuStore_AddItem(playerid, 7, 	19617, 	"MP3 Player",		2400);
			MenuStore_AddItem(playerid, 8, 	18632, 	"Fishing Rod",		1000);
			MenuStore_AddItem(playerid, 9, 	19063, 	"Fish bait", 		200,		"", 0.0, true,	 20);
			MenuStore_AddItem(playerid, 10,	19823, 	"Muriatic Acid", 	1500,	"", 0.0, true,	 10);
			MenuStore_AddItem(playerid, 11, 2709, 	"Baking Soda", 		1290,	"", 0.0, true,	 10);
			MenuStore_AddItem(playerid, 12, 19039, 	"Pocket Watch", 	850);
			MenuStore_AddItem(playerid, 13, 19167, 	"GPS System", 		2000);
			MenuStore_AddItem(playerid, 14, 1650, 	"Gasoline Can", 	100,	"", 0.0, true,	 20);
			MenuStore_AddItem(playerid, 15, 19088, 	"Rope",		 		150,		"", 0.0, true,	 10);
			MenuStore_AddItem(playerid, 16, 18912, 	"Blindfold", 		3500,	"", 0.0, true,	 10);
			MenuStore_AddItem(playerid, 18, 19163, 	"Mask", 			20000);
			MenuStore_AddItem(playerid, 19, 365, 	"Repairkit", 	5000);
			MenuStore_Show(playerid, Menu_Market, "24/7 Supermarket");
		}
`
