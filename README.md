本材质是为Hypixel&Domcer Megawalls小游戏特制的覆盖材质包(需解压使用)

请确保开启:视频设置>品质>连接纹理&自定义物品&自发光纹理 确保材质包正常工作

如有建议或bug反馈可以联系制作者Bilibili@ohSnowy(https://space.bilibili.com/437627678)

材质部分创意来源于FurfSky Reborn材质包(https://hypixel.net/threads/furfsky-reborn-1-4-1-rosettas-wares.4101579/)


-----------------------------------------------------------------------------------
材质支持服务器中文和英文语言,目前功能为: 

	1---放大治疗品(药水 牛奶桶等)及钻石相关物品,特殊物品（海盗宝藏 绿宝石掉落物盔甲等)
		//(如果想删除此效果，需把"\assets\minecraft\models"路径下"item"文件夹以及
		"\assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\Amror"路径下的"model"文件夹,
		"\assets\minecraft\mcpatcher\cit\Megawalls resourcepacks"路径下的"Swords","other","bows"文件夹删除)
		//(海盗特殊物品纹理都位于宝藏特殊模型同文件夹下,可以使用同名纹理替换)


    2---界面优化:
		(1)更好的皮肤选择,职业购买/选择界面  美化皮肤&职业选择界面的头颅模型，染料选择器   使其更方便预览选择
		(2)任务npc界面优化(待接取的任务会显示黄色感叹号,已接取但未完成的任务会显示红色的叉号,已经完成的任务会显示绿色对号.)
		(3)精通界面优化(现在P1/P2/P3/P4职业会在职业选择的界面显示特殊的纹理皮肤) 注:所有纹理图都取自Hypixel,D服自创职业因为找不到精通皮肤图文件所以只有初始职业皮肤图,无精通特殊图.(P1皮肤是我随机挑选的,p2为传奇皮肤,p3为p3皮肤,p4为p3加金色边框)
        //（如果想删除头颅预览效果只需把"\assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\Skull(Select)"路径下的"Skull"文件夹删除即可
	 	 同理删除染料选择器需删除在同路径下的"Select"文件夹)
		//  (如果想移除职业选择界面头颅图材质需在"\assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\Skull(Select)"路径下删除"Menu"文件夹)
		//(删除任务界面:在"assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\Quest"内把"quest"文件夹删除即可)
		//(删除精通界面:在"assets\minecraft\mcpatcher\cit\Megawalls resourcepacks"路径下删除"Prestige"文件夹即可)

	3---屏障方块标识线:在紧贴屏障放置木板 原石 泥土时纹理会发生变化,在靠近屏障的一边有白线标识
	 	//(如果想删除此纹理覆盖需在"\assets\minecraft\mcpatcher"路径下把"ctm"文件夹删除)



	4---盔甲耐久提示:当铁/钻石盔甲耐久不足会改变其纹理,显示不同颜色的线,[胸甲/裤子]耐久小于100/50/20会显示绿线/黄线/红线,[头盔/鞋子]耐久小于80/50/20会显示绿线/黄线/红线
		//(如果想删除此效果请删除"\assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\Amror"路径下的"iron""diamond"文件夹)
		//v1.5.0版本后不会再出现绿线



   	5---第三人称手持补给品预览:当手持药水或金苹果奶桶等道具时第三人称视角下的物品显示位置将会更容易被看见
	
	****提示****    如果显示物品朝下请检查是否开启更改1.7手持物品的功能。(以LunarClient举例:检查Mdos中的1.7 Visuals中的Third Person Held Items,当功能		打开时将不能正确显示补给品的位置)
	 
		//(如果想删除此效果需更改补给品的json文件,以凤凰药举例:首先需找到"assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\other\Pot		\Phoenix's_Tears_of_Regeneration"路径下的"bottle_splash.json"文件,打开找到:
             		 thirdperson": {
			"rotation": [ 204, 0, 0 ],
        			"translation": [ -0.25, -0.5, -2.5 ],
        			"scale": [ 0.55, 0.55, 0.55 ]
			},
	替换其中括号内的数值为:
		"thirdperson": {
             			"rotation": [ -90, 0, 0 ],
            			"translation": [ 0, 1, -3 ],
            			"scale": [ 0.55, 0.55, 0.55 ]
        			},
	即可修改为原版显示效果
		//修改职业药水手持预览需要到"\assets\minecraft\mcpatcher\cit\Megawalls resourcepacks\other\Pot"路径下删除"Etc"文件夹
		//金苹果和牛奶桶"\assets\minecraft\models\item"



	6---夜视效果
		//(如果想删除此效果请删除"assets\minecraft\mcpatcher\lightmap"路径下的"lightmap"文件夹)



	7---方块破坏无粒子
		//(在"\assets\minecraft\models"路径下删除"block"文件夹即可移除此效果)



	8---红色箭头覆盖
		现在在玩家身上的箭会显示红色的箭头(不会影响其他未射到玩家身上的箭头纹理)
		//(在"\assets\minecraft\textures"路径下删除"entity"文件夹即可移除此功能)
-----------------------------------------------------------------------------------



Hypixel
    特殊物品名(游戏中暂无中文翻译):

      海盗(pirate)  
          Matey Rapier{亡灵杀手III  铁剑}
          Matey Spicy Sword{火焰附加I 铁剑(仅能使用6次)}
          Matey Coconut Bow{冲击I 弓}
          Matey Voodoo Bow{力量I 弓}
          Matey Trousers{保护I 深海探索者II 铁裤}

      刺客(Assassin)
          Assassin 剑{Assassin \u5251}

      鼹鼠(Moleman)
          Junk Apple{附魔苹果}

      牛(Cow)
          Ultra Pasteurized Milk Bucket{牛奶桶}



--------------------------------------------------------------------------------------



更新日志:
	更新头颅预览，调整物品放大的尺寸  2022/1/10

	更新尝试支持D服超级战墙  2022/2/22

	更新方块衔接材质（在屏障旁放置部分方块会显示特殊线） 2022/5/7

	v1.0.0 修复bug并完善材质,修改版本号为1.0.0  2023/5/8
	
	v1.1.0 新添加效果方块无粒子,夜视,更好的第三人称手持补给显示 2023/8/29

	v1.2.0 修复d服不法者装备显示bug 2023/9/18

	v1.3.0 添加盔甲耐久显示功能,职业菜单材质更新,修复部分bug 2023/10/24

	v1.4.0 添加部分职业菜单&任务&精通界面材质,新添加红色箭头覆盖,修复部分bug 2023/11/28

	v1.5.0 现在菜单中p1/p2职业也会显示特殊的纹理,盔甲耐久显示不会再出现绿线,并且为海盗的特殊物品添加了纹理(无耐久胸甲),皮肤购买界面也添加了部分纹理,修复部分错误显示纹理的bug(饮用喷溅药水显示等...)(由于d服特殊物品没有特殊名称,如果给耐久胸甲添加纹理会导致其他部分纹理无法正常显示) 2024/2/2

	v1.6.0 修改选择职业的物品为对应的皮肤头颅,为新更新的界面提供纹理更新,修复了力量弓纹理冲突的bug,放大了补给品及手持显示,新添加了彩虹箭头覆盖显示测试 2024/7/10
