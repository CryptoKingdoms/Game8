# Crypto Kingdoms

## Introduction

Crypto Kingdoms is a strategy game. (It is not a gambling game.) New players are given a kingdom in which they are able to recruit various types of units, build buildings, attack, spy, and sabotage other player kingdoms in order to gain the most gold at the end of the game. The kingdom with the most gold at the end of the game wins a prize pool of Ethereum! The game is ran openly, securely, and unstoppably on the decentralised Ethereum blockchain.

The game lasts 33 days and has a turn that occurs every 11 hours. When the turn occurs the amount of gold and soldiers in each kingdom is updated based on the current kingdom's stats (e.g. number of mining camps and barracks). When the last turn occurs the game will end and the kingdom with the most gold will be the winner. This winning kingdom's Ethereum address will have transferred to it an Ethereum prize.

## Game Rules

### Basic Rules

A player may join any time after the game has started. The starting gold and actions are balanced to give all players a chance of winning so long as they join the game before it is no more than half way through. All players have a maximum amount of actions that they are able to spend within the game, and so the overall game cost is estimated and displayed before joining.

A player receives 1 action every turn (11 hours) which may be used at any time during the game time. The following actions can be made.

    * Recruit Soliders
        - Soldiers provide good attack power but die easily.

    * Recruit Spies
        - Spies provide small attack power but cannot be killed.
        - Spies require a hovel to live.
        - Spies are used with the Espionage action.

    * Summon Wizards
        - Wizards provide a medium attack power and are hard to kill.
        - Wizards provide gold every turn.
        - Wizards require a hovel to live.

    * Train Dragons
        - Dragons provide a large attack power and are very hard to kill.
        - Dragons are used with the Sabotage action.

    * Build Hovels
        - Hovels provide gold every turn.
        - Required for spies or wizards.

    * Build Mining Camps
        - Mining camps provide gold every turn.

    * Build Banks
        - Banks provide interest on the gold stored in the player's kingdom at every turn.

    * Build Barracks
        - Barracks provide soldiers every turn and a small amount of defence power.

    * Build Castles
        - Castles provide a large amount of defence power and a small amount of gold and soldiers every turn.
        - Castles are used by the defending kingdom with the Sabotage action.

    * Attack
        - A player may select a number of soliders (up to all) to send to attack another player's kingdom in order to try to steal a fraction of their gold.
        - An attack power is calculated for the attacker as; (soldiers sent  * solider attack power + spies * spy attack power + wizards * wizard attack power + dragons * dragon attack power)
        - A defence power is calculated for the defender as; (soliders * solider attack power + spies * spy attack power + wizards * wizard attack power + dragons * dragon attack power + barracks * barracks defence power + castles * castle defence power)
        - The player with the largest force in the conflict wins.
        - If the attack is successful, you will gain a random fraction of gold from the other kingdom proportional to the amount by which you beat the other kingdom.
        - Some amount of the soldiers that were sent to attack will be killed, and wizards and dragons may also be killed.
        - If the attack is successful, you may still lose soldiers, wizards, and dragons, but you will lose less.
        - Some amount attacked kingdom's soldiers, wizards, and dragons will also be killed.
        - The narrower the victory or defeat, the more gold will be stolen and the larger the number of casualties.

    * Espionage
        - If the kingdom has more than half the spies in the target kingdom, the Espionage will be successful.
        - If the Espionage is successful the target kingdom's amount of gold, soliders, mining camps, dragons, banks, or castles may be revealed.
        - If the Espionage is unsuccessful the espionaging kingdom's number of spies will be revealed.

    * Sabotage
        - If the target kingdom has less dragons and castles combined than the sabotaging kingdom has dragons, a fraction of the target kingdom's gold, hovels, mining camps, or banks may be destroyed.
        - Dragons may also be lost on both sides during a sabotage.

## Detailed Rules

Hover your cursor over action buttons and your kingdom's stats and actions in the game's website client over at www.CryptoKingdoms.org to see further details. On a mobile device, tap on once for details, and tap again to use an action.

## Complete Rules

Check out the file CryptoKingdoms.sol for the full Ethereum smart contract program source code for the complete programmed rules that run on the Ethereum blockchain. You shouldn't need to read the code to be able to play Crypto Kingdoms, the website should explain everything, but the code is there if you want it!

## Fees

New players must deposit Ethererum which is used to pay for the winner's prize and hosting of the game. Ethereum blockchain transaction / execution fees must also be paid to cover the costs of making actions within the game. All costs are included in the overall Ethereum game cost estimate which is displayed to players before joining.

Actions within the game are stored on a permenant, everlasting blockchain record. There is no stopping the game once it has started, and no altering of the rules. The game host reserves the right to change a kingdom's name but that is all. The smart contract is open source and readily available for easy verification. And if you win a game of Crypto Kingdoms, your kingdom's name and stats will be enshrined forever!

## Contact

Please contact admin@cryptokingdoms.org with any questions, for any help, or to be added to the mailing list to be notified when a new game is about to start.

