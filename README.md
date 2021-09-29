# PlayerLevel
Added a Level system to the game! The player does not need to execute command to level up. All of this is done automatically! The Skript is fully configurable!

------
 Need of:
 - TuSKe
 - SkRayFall
 - SkQuery
 - Sk-NbeeT
 - Skellett-Legacy
 - SkBee
 ----------

Useful admin command:

      /editxp <player> <number>
        Modify the number of xp the player has.
        Permission: PlayerLevel.editxp
      
      
      /editrequiredxp <player> <number>
      or
      /editrxp <player> <number>
        Modify the number of xp the player needs to level up (personal value for each player)
        Permission: PlayerLevel.editrequiredxp
      
      
      /editlevel <player> <number>
        Change the player's level.
        Permission: PlayerLevel.editlevel
      
      
      /resetalllevel <player>
        Start the player over from the beginning! Are XP, level, xp required and reset to the starting one.
        Permission: PlayerLevel.resetalllevel
      
      
      /!\ Required Skript "PlayerLevel-Notif" /!\
              /playerlevel reload
              ! Reload the skript !
              Permission: PlayerLevel.reload
        
Helpful player commands:
      
      
      /playerlevel info <player>
        See the player's level of the argument.
        Permission: PlayerLevel.InfoPlayer
      
      /playerlevel info
        See its own level and information.
      
      /playerlevel about
        See the skript information
 
---------------


PlayerLevel-Notif:
--

      /Messagemaxlevel <true/false/info>
      or
      /msgmaxlvl <true/false/info>
        Hide the player's message when he reaches max level!
        All players can execute this command! It's a personal command!
