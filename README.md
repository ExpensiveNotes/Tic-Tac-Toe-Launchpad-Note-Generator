# Tic-Tac-Toe-Launchpad-Note-Generator
 Naughts and Crosses (TIC TAC TOE) - MIDI Note Generator.
     by John Melki-Wegner (AKA "Expensive Notes" on YouTube)

    Using a Teensy 4.1 with USB Host to send and recieve messages with a Launchpad Mini Mk3

    Make sure the Launchpad in Programmer mode after each reboot by:
    Long Press the Session pad and then press StopMuteSolo then Session and then User. (Press pads consecutively)

    Notes: Programmer Mode assumes a 10x10 grid except that row 10 and column 10 are off the screen
            MIDI notes are received from the 8x8 grid
            Bottom left corner is "origin" (1,1)
            The Black pads send MIDI CC and send the message on press and release of the pad! I use code to ignore the release message

    Launchkey Orientation: Arrow keys at the bottom (right)
