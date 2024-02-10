# Creating Your First NPC

Start by creating your first NPC. You can use the in-game command, `/npc create` to design characters with unique
appearances and behaviors. Consider crafting NPCs that enhance your server's role play or gameplay experience

From there, you will be greeted by the NPC configuration menu. You can change the NPC's name, skin, armor, persistence,
actions, and much more!

## Changing the NPC's Name

To change an NPC's name, open the editing menu. This will be opened, initialized to an NPC with no data, if you just ran
the `/npc create` command.

- {type="decimal"}Click on the name tag.
- Type the desired name in [MiniMessage format](https://docs.advntr.dev/minimessage/format.html) into the Minecraft Chat
- Click your enter key to finalize the name.

![Video of setting NPC Name](set-npc-name.gif)

## Changing the NPC's Skin

To change an NPC's skin, open the editing menu. This will be opened, initialized to an NPC with no data, if you just ran
the `/npc create` command.

### Method 1: Skin Catalogue {collapsible="true"}

- {type="decimal"} Open the skin editor by clicking on the player head with a missing texture icon
- Open the skin catalogue by clicking on the armor stand
- Browse and select your desired Skin!

### Method 2: Import From Player {collapsible="true"}

- {type="decimal"} Open the skin editor by clicking on the player head with a missing texture icon
- Click the anvil to select importing from a player name
- Type the player's name to import the skin from. <note>This imports the player's CURRENT skin, and it will not change
  if the player changes their skin.</note>
- Hit "enter" to confirm

### Method 3: Import From URL {collapsible="true"}

- {type="decimal"} Open the skin editor by clicking on the player head with a missing texture icon
- Click the Book & Quil to select importing from a URL
- Paste the URL into the chat
- Hit "enter" to confirm

## Changing the NPC's Equipment

To change an NPC's equipment, open the editing menu. This will be opened, initialized to an NPC with no data, if you
just ran the `/npc create` command.

- {type="decimal"} Open the equipment editor by clicking on the armor stand.
- Click any slot with an item to equip it on the NPC. <note>For Boots, Leggings, and Chest plates, the item type must
  be compatible with the slot.</note>
- To reset a slot, right-click on it.
- Alternatively, you can import your current armor by clicking the armor stand in the top right of the menu.

<note>
    The armor is serialized as the EXACT item you supplied. This means the NPC can have items with:
    <list>
       <li>
           Custom Model Data
       </li>
       <li>
           Colors (Leather Armor)
       </li>
       <li>
           Enchantments
       </li>
    </list>
</note>


## Changing the NPC's Persistence

What is NPC Persistence? {collapsible="true"}
: NPC Persistence determines if the NPC should persist or stay on server restarts.


To change an NPC's persistence, open the editing menu.
This will be opened, initialized to an NPC with no data, if you
just ran the `/npc create` command.

By clicking the bell, you can toggle 
<tooltip term="NPC Persistence">NPC Persistence</tooltip>.

## Changing the NPC's Facing Direction
The facing direction is the direction the NPC faces when there isn't a player within five blocks, and it doesn't have
<tooltip term="Tunnel Vision"> Tunnel Vision</tooltip>. The possible options are the cardinal directions and the yaw
of the player currently editing the NPC.

## Changing the NPC's Tunnel Vision

What is Tunnel Vision?
: Tunnel vision determines if the NPC looks at nearby players. 

This can be toggled by clicking the spyglass under the equipment menu.

## Adding Actions to an NPC
To change the NPC's Actions, first open the editing menu.
This will be opened, initialized to an NPC with no data, if you
just ran the `/npc create` command.

From there, ensure the NPC is interactable.
Non-interactable NPCs cannot have actions.
This can be achieved by clicking
on the dead bush if it is in the menu.
You will know the NPC is interactable if you can see a Recovery Compass in the
bottom right of the menu.

You can then add actions by clicking on the Lilly pad. 

For a more in-depth guide to using Actions, look [here](Using-the-Action-System.md).

