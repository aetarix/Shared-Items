# Shared-Items
## Add on items for QBCore based servers.
## Simply add the following into your qbcore/shared/items.lua
## Move images from the images folder into your inventory/html/images folder.
## Restart server and your done. Hope this helps
## Join the Discord for other helpful scripts and snippets: https://discord.gg/fTGm36CERk

	-- Food ITEMS
	['sandwich1'] 					 	= {['name'] = 'sandwich1', 			 	  		   ['label'] = 'Egg Sandwich', 				['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich1.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich2'] 					 	= {['name'] = 'sandwich2', 			 	  		   ['label'] = 'Ham Sandwich', 				['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich2.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich3'] 					 	= {['name'] = 'sandwich3', 			 	  		   ['label'] = 'Chicken Sandwich', 			['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich3.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich4'] 					 	= {['name'] = 'sandwich4', 			 	  		   ['label'] = 'Tuna Sandwich', 			['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich4.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich5'] 					 	= {['name'] = 'sandwich5', 			 	  		   ['label'] = 'Vegemite Sandwich', 		['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich5.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich6'] 					 	= {['name'] = 'sandwich6', 			 	  		   ['label'] = 'Peanut Butter Sandwich', 	['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich6.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich7'] 					 	= {['name'] = 'sandwich7', 			 	  		   ['label'] = 'Jam Sandwich', 				['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich7.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['sandwich8'] 					 	= {['name'] = 'sandwich8', 			 	  		   ['label'] = 'BLT Sandwich', 				['weight'] = 175, 			['type'] = 'item', 		['image'] = 'sandwich8.png', 			['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},

	['candy1'] 					 	 	= {['name'] = 'candy1', 			 	  		   ['label'] = 'Twix', 						['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy1.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy2'] 					 	 	= {['name'] = 'candy2', 			 	  		   ['label'] = 'Crunchie', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy2.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy3'] 					 	 	= {['name'] = 'candy3', 			 	  		   ['label'] = 'Mars Bar', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy3.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy4'] 					 	 	= {['name'] = 'candy4', 			 	  		   ['label'] = 'Freddo Frog', 				['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy4.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy5'] 					 	 	= {['name'] = 'candy5', 			 	  		   ['label'] = 'Picnic', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy5.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy6'] 					 	 	= {['name'] = 'candy6', 			 	  		   ['label'] = 'Dream', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy6.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy7'] 					 	 	= {['name'] = 'candy7', 			 	  		   ['label'] = 'Kinder Bueno', 				['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy7.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy8'] 					 	 	= {['name'] = 'candy8', 			 	  		   ['label'] = 'Twirl', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy8.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy9'] 					 	 	= {['name'] = 'candy9', 			 	  		   ['label'] = 'Boost', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy9.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['candy10'] 					 	= {['name'] = 'candy10', 			 	  		   ['label'] = 'Snickers', 					['weight'] = 75, 			['type'] = 'item', 		['image'] = 'candy10.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},

	['snack1'] 					 	 	= {['name'] = 'snack1', 			 	  		   ['label'] = 'Original Chips', 			['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack1.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack2'] 					 	 	= {['name'] = 'snack2', 			 	  		   ['label'] = 'Chicken Chips', 			['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack2.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack3'] 		 			 	 	= {['name'] = 'snack3', 			 	  		   ['label'] = 'Salt & Vinegar Chips', 		['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack3.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack4'] 					 	 	= {['name'] = 'snack4', 			 	  		   ['label'] = 'Barbeque Chips', 			['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack4.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack5'] 					 	 	= {['name'] = 'snack5', 			 	  		   ['label'] = 'Light & Tangy Chips', 		['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack5.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack6'] 					 	 	= {['name'] = 'snack6', 			 	  		   ['label'] = 'Burger Rings', 				['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack6.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack7'] 					 	 	= {['name'] = 'snack7', 			 	  		   ['label'] = 'Cheese Twisties', 			['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack7.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack8'] 					 	 	= {['name'] = 'snack8', 			 	  		   ['label'] = 'Cheese Doritos', 			['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack8.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack9'] 					 	 	= {['name'] = 'snack9', 			 	  		   ['label'] = 'Cheezels', 					['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack9.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['snack10'] 					 	= {['name'] = 'snack10', 			 	  		   ['label'] = 'French Fries', 				['weight'] = 125, 			['type'] = 'item', 		['image'] = 'snack10.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},

	['drink1'] 					 	 	= {['name'] = 'drink1', 			 	  		   ['label'] = 'Coca Cola Can', 			['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink1.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink2'] 					 	 	= {['name'] = 'drink2', 			 	  		   ['label'] = 'Pepsi Can', 				['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink2.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink3'] 					 	 	= {['name'] = 'drink3', 			 	  		   ['label'] = 'Sunkist Can', 				['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink3.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink4'] 					 	 	= {['name'] = 'drink4', 			 	  		   ['label'] = 'Lift Can', 					['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink4.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink5'] 					 	 	= {['name'] = 'drink5', 			 	  		   ['label'] = 'Sprite Can', 				['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink5.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink6'] 					 	 	= {['name'] = 'drink6', 			 	  		   ['label'] = 'Dr Pepper Can', 			['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink6.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink7'] 					 	 	= {['name'] = 'drink7', 			 	  		   ['label'] = 'Solo Can', 					['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink7.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink8'] 					 	 	= {['name'] = 'drink8', 			 	  		   ['label'] = 'Passiona Can', 				['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink8.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink9'] 					 	 	= {['name'] = 'drink9', 			 	  		   ['label'] = 'Fanta Can', 				['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink9.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink10'] 					 	= {['name'] = 'drink10', 			 	  		   ['label'] = 'Mountain Dew Can', 			['weight'] = 150, 			['type'] = 'item', 		['image'] = 'drink10.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink11'] 					 	= {['name'] = 'drink11', 			 	  		   ['label'] = 'Coca Cola 600ml', 			['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink11.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink12'] 					 	= {['name'] = 'drink12', 			 	  		   ['label'] = 'Pepsi 600ml', 				['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink12.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink13'] 					 	= {['name'] = 'drink13', 			 	  		   ['label'] = 'Sunkist 600ml', 			['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink13.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink14'] 					 	= {['name'] = 'drink14', 			 	  		   ['label'] = 'Lift 600ml', 				['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink14.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink15'] 					 	= {['name'] = 'drink15', 			 	  		   ['label'] = 'Sprite 600ml', 				['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink15.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink16'] 					 	= {['name'] = 'drink16', 			 	  		   ['label'] = 'Dr Pepper 600ml', 			['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink16.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink17'] 					 	= {['name'] = 'drink17', 			 	  		   ['label'] = 'Solo 600ml', 				['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink17.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink18'] 					 	= {['name'] = 'drink18', 			 	  		   ['label'] = 'Passiona 600ml', 			['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink18.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink19'] 					 	= {['name'] = 'drink19', 			 	  		   ['label'] = 'Fanta 600ml', 				['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink19.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink20'] 					 	= {['name'] = 'drink20', 			 	  		   ['label'] = 'Mountain Dew 600ml', 		['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink20.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink21'] 					 	= {['name'] = 'drink21', 			 	  		   ['label'] = 'Mount Franklin 600ml', 		['weight'] = 275, 			['type'] = 'item', 		['image'] = 'drink21.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink22'] 					 	= {['name'] = 'drink22', 			 	  		   ['label'] = 'Hot Chocolate', 			['weight'] = 200, 			['type'] = 'item', 		['image'] = 'drink22.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink23'] 					 	= {['name'] = 'drink23', 			 	  		   ['label'] = 'Coffee', 					['weight'] = 200, 			['type'] = 'item', 		['image'] = 'drink23.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
	['drink24'] 					 	= {['name'] = 'drink24', 			 	  		   ['label'] = 'Tea', 						['weight'] = 200, 			['type'] = 'item', 		['image'] = 'drink24.png', 				['unique'] = false, 		['useable'] = true, 	['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'Nice to eat'},
