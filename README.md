TST 任务书

使用 DeepSeek 机翻版本，目前由Straw完成第一次人工校对，你可以 fork 这个仓库，创建自己的翻译，或者提交你觉得有问题的翻译，以及提交更好的翻译方式来完善翻译，目前该版本已适配274

使用方法

将 zh_CH.lang 内容最追加到./config/txloader/load/betterquesting/lang/zh_CN.lang 文件末尾，注意是追加不要覆盖，然后重启游戏即可，如果翻译未变化，可以输入 /bq_admin default load 重新加载任务书

# Twist-Stuff

My Twist Space Repo - QBs &amp; Info

Instructions for how to download the Twist Questbook using the Easy Way:

The DefaultQuests is the entire QuestBook from GTNH, including a chapter on Twist that I made.

To add it to your pack:

First, click the blue `<> CODE` button and download the ZIP

1. Go to configs
2. Navigate to the betterquesting folder
3. DELETE the "DefaultQuests" folder.
4. Download the "DefaultQuests" Folder that exists on this repository
5. Copy it to the betterquesting folder; this will add the Twist Quest Page
6. Go in-game and type the command `/bq_admin default load` (YOU DO NOT NEED OP FOR THIS), this will load the questbook with all the Twist Quests added. Because quests are saved world side, you will not lose any progress with your current quests, but please contact Aditya if you run into any troubles

To install it the Hard Way (manually, not recommended):

1. Download all the folders separately so as not to get confused, including the QuestLinesOrder.txt
2. Copy the Twist Space Technology Folder in the QuestLines folder from this repository to the `QuestLines` folder in the `DefaultQuests` Folder.
3. Copy the Twist Space Technology Folder in the Quests folder from this repository to the `Quests` folder in the `DefaultQuests` Folder.
4. Replace the `QuestLinesOrder.txt` in your INSTANCE folder with the one you downloaded from this repository.

Reload the QuestBook after using the default load command. This should work, but please don't hesitate to contact me in my Discord or the Twist Discord if you have any questions.
以下为安装方法的翻译版本，仅提供简单方法的译文，为保证其他中文翻译不被覆盖
建议在安装完成后，重新按照中文wiki的安装翻译的方法安装翻译，这不会导致tst任务被覆盖：
1.找到你安装GTNH的文件夹，找到.minecraft/configs/betterquesting
2.删除Defaultquests文件夹，下载本库所提供的Defaultquests文件夹
3.将其复制到原来的betterquesting文件夹
4.输入指令：/bq_admin default load，若你为服务器管理员，此步骤可跳过。