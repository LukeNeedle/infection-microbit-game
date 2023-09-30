# infection-microbit-game
A multiplayer game played with the BBC Micro:Bit

This game is based off the game team tag.

## Setup

Please flash all but one of the Micro:Bits with the Game Client hex file.

Please flash all but one of the Micro:Bits with the Game Host hex file.

Power on each Micro:Bit, they should start to read "Searching". They are now waiting for the Game Host to confirm the difficulty. Once they do the display should start reading Ready.

The Game Host can set the difficulty of the game, they do this by pressing A to subtract one and B to add one.

| Difficulty value | Easiest for |
|:----------------:|-------------|
| 0	               | Players     |
| 1	               | -           |
| 2	               | Game host   |

Once the selected difficulty displayed is equal to the desired difficulty shake the Micro:Bit until it starts to read "Sending", you are now ready to begin.

## Playing

Once all of the Micro:Bits have outputted "Ready" shake the game master Micro:Bit again, all of the User Micro:Bits should be counting down from 3. On go everyone can run, except the Game Host who has a timer counting down from 60.

The 60 seconds should give all of the other players enough time to get out of radio distance of the Game Host.

When a player reaches zero health they become Infected, this means that they start Infecting other players, decreasing their health.

## Ending

Once everyone has become infected, the Game Host should press both A and B at the same time to end the game, once everyone’s display has said “Searching” again the Game Host should shake the device to go back to the difficulty menu.

## How to flash a BBC Micro:Bit

![How to flash a BBC Micro:Bit](https://python.microbit.org/v/3/static/media/transfer-hex-win.e71df84067fad7538488.gif)

https://python.microbit.org/v/3/static/media/transfer-hex-win.e71df84067fad7538488.gif
