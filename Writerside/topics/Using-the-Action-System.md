# Using the Action System

## What is the Action System?
The action system is a flexible and powerful extension of other NPC plugins. With CustomNPCs, you can trigger actions
to occur on NPC Interaction. With the new changes coming in 1.7, custom actions can be registered using the API. As of
writing, version 1.6 provides the following 12 default actions.

- Run Command
- **Display Title**
- **Send Message**
- **Send Actionbar**
- Play Sound
- Teleport Player
- Give Exp
- Remove Exp
- Give Effect
- Remove Effect
- Send to Bungeecord/Velocity Server
- Toggle Following 

<warning>
    The `Toggle Following` action is an unstable feature, and therefore is still under heavy development.
</warning>
    <tip>
        The 
        <control>
            Bolded
        </control>
        actions support
        <a href="https://www.spigotmc.org/resources/placeholderapi.6245/">
            PlaceHolderAPI
        </a>
    !
</tip>
<tip>
    The `Run Command` action runs the command as the interacting player, not the console.
</tip>

## Adding an Action to an NPC
To add an action to an NPC, first open the editing menu. From there, open the action menu, by clicking on the Recovery
Compass. From there you can edit an existing action by left-clicking on it. To remove an action, right-click it. To
add a new action, click the lilly pad. From there, select the action you would like to add. After selecting the action,
you will be presented with a menu to customize the action. Every action, with the exclusion of `Toggle Following`, can
be delayed. Every action customizer menu will present you with two buttons at the top center of the menu to adjust to
delay. From there, you can adjust the action's values to suit your need. Once you are done, click on the lilly pad to 
confirm the action. From here, you can add more actions if you would like. After you are finished adding more actions,
press the arrow in the bottom left to return to the main NPC menu. To apply the changes you made, click the lime dye
in the center of the menu.

There are a few types of items to be expected in an action customizer menu.

> Some values are bounded and cannot exceed certain values.


Clock
: A clock represents a value display. Clicking this doesn't do anything.

Lime Dye
: A lime dye represents a button to increment a value.
: Left-clicking these increments the value by **1**
: Right-clicking these increments the value by **5**
: Shift-clicking these increments the value by **20**

Red Dye
: A red dye represents a button to decrement a value.
: Left-clicking these decrements the value by **1**
: Right-clicking these decrements the value by **5**
: Shift-clicking these decrements the value by **20**

Candles
: Candles represent something with two states. A good example is the Give/Remove EXP actions as they can Give/Take
either EXP Levels OR Points, but not both. (In the same action, anyway).

Hanging Sign
: Hanging signs represent an item to trigger the input of textual input. A good example of this is the `Send Message`
action, as it requires textual input for the message to be sent.

Comparator
: A Comparator is the button to get to the condition editor, covered [here](Using-Conditions-Within-Actions.md).
