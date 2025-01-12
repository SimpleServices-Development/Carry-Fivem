# Carry-Fivem V1.2.1

# SET UP LIKE A BOSS:
1. Create a folder in resources and call it [Simple-Services]
2. Download Carry-Fivem
3. Drag Carry-Fivem into [Simple-Services]
4. Ensure the folder in your server.cfg: ensure [Simple-Services]


# USE:
Just do /carry nearby a person to carry them and /carry to drop.

# F8 BINDING FOR EASY USE:
1. Click F8
2. Paste: bind keyboard "_your key of choice (I USE 'N' IN THE SHOWCASE)_" "carry"
3. Enter
Whenever you click your key of choice you will carry a person if they are nearby.

# RECOMMENDED ANIMATIONS IF YOU WISH TO CHANGE THE BASIC ONE:
# Starting Code
```                      
local carry = {
	InProgress = false,
	targetSrc = -1,
	type = "",
	personCarrying = {
		animDict = "missfinale_c2mcs_1",
		anim = "fin_c2_mcs_1_camman",
		flag = 49,
	},
	personCarried = {
		animDict = "nm",
		anim = "firemans_carry",
		attachX = 0.27,
		attachY = 0.15,
		attachZ = 0.63,
		flag = 33,
	}
} 
```
# Option Change (Carrys them infront in your hands)
```
local carry = {
	InProgress = false,
	targetSrc = -1,
	type = "",
	personCarrying = {
		animDict = "anim@heists@box_carry@",
		anim = "idle",
		flag = 49,
	},
	personCarried = {
		animDict = "amb@code_human_in_car_idles@generic@ps@base",
		anim = "base",
		attachX = 0.27,
		attachY = 0.15,
		attachZ = 0.63,
		flag = 33,
	}
}
```
# Discord: https://discord.gg/nxVGTtZBe2
# Showcase: https://youtu.be/wnNpxBfcyIA
# Install Showcase: https://youtu.be/xI4VDluv-sM

Edited version of: https://github.com/rubbertoe98/FiveM-Scripts/tree/master/CarryPeople

Before anyone says that it is a stolen code, I have linked the original creators page above and they have said in their read me, and I quote: "Feel free to make improvements". 
