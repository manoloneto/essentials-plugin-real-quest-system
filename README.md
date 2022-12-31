[![pokémon essentials brasil](https://scontent.fpoa28-1.fna.fbcdn.net/v/t1.6435-9/46470529_1462922783841780_6425690319458664448_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=8631f5&_nc_ohc=Xeo87fOD22wAX8-OGXW&_nc_ht=scontent.fpoa28-1.fna&oh=00_AfB-P_gkVTpXJn6rDjzB0XfFAu9ixx7K7r97ul-11O5Zpw&oe=63CD8467)](https://www.facebook.com/groups/essentialsbr)

# Real Quest System

[![plugin version](https://img.shields.io/badge/Plugin%20version-1.0.0-brightgreen)](https://www.pokecommunity.com/showthread.php?t=488598) [![essentials version](https://img.shields.io/badge/Essentials%20version-20+-blue)](https://essentialsdocs.fandom.com/wiki/Essentials_Docs_Wiki)

> A plugin to Pokémon Essentials (RMXP). 
> A simple quest system for Pokémon Essentials v20 or higher.

## Install

You can download this repository by click on **Code** blue button and next on **Donwload ZIP** option.

In your PC, move the **all content of Real Quest System folder** to your **project folder**.

That's it.

## Settings

In the `000_settings.rb` file, you will found some options to customize the plugin.

Create your quests by adding news lines follow the template in the settings file.

Turn **USE_GENERATION_IV_STYLE** setting into **true** for the plugin to stay with the fourth generation visual style.

Turn the **DEBUG_MODE** setting into **true**, on **Real Core** plugin, to show debug messeges on debug console.

## How to use

Use the script `Real.addQuest(:YOUR_QUEST_ID_HERE)` to **add** a quest to your players TO-DO list.

Use the script `Real.completeQuest(:YOUR_QUEST_ID_HERE)` to **set complete** a quest in your players TO-DO list.

Use the script `Real.removeQuest(:YOUR_QUEST_ID_HERE)` to **remove** a quest of your players TO-DO list.

Use the script `Real.isQuestCompleted(:YOUR_QUEST_ID_HERE)` to **check** if the player complete the quest.

To call **TO-DO List** screen, press the key that you set in **settings** file. 
By default this key is **O** *(of Olive)*.

> **WARNING** 
> - The **Real Core** plugin is required to use **all of my plugins**.
> - The **Generation IV style** is a test, and it may not work as expected.