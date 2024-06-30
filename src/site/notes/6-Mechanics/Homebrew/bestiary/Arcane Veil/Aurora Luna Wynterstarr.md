---
{"dg-publish":true,"permalink":"/6-mechanics/homebrew/bestiary/arcane-veil/aurora-luna-wynterstarr/"}
---

```statblock
layout: Basic 5e Layout
image: "z_Assets/NPCs/Arcane Veil Tokens/aurora luna wynterstarr.png"
#image (example): "token/aboleth.webp"
name: "Aurora Luna Wynterstarr"
size: "Medium"
type: "humanoid"
subtype: "dhampir"
alignment: "chaotic good"
ac: 15
ac_class: "Studded Leather Armor"
hp: 48
hit_dice: "8d8+16"
speed: "30 ft."


# ABILITY SCORES
stats:
- 10  # Strength
- 16  # Dexterity
- 14  # Constitution
- 12  # Intelligence
- 10  # Wisdom
- 18  # Charisma


# SAVES
saves:
  Dexterity: 6
  Charisma: 7


# Skills
skillsaves:
  Performance: 10
  Persuasion: 7
  Stealth: 6


# IMMUNITIES, RESISTANCES AND VULNERABILITIES
damage_vulnerabilities: "" 
damage_resistances: "Necrotic"
damage_immunities: ""
condition_immunities: ""


senses: "Darkvision 60 ft., Passive Perception 10"
languages: "Common, Elvish, Undercommon"
cr: 4


# TRAITS
traits:  
- name: "Regeneration"
  desc: "Aurora regains 5 hit points at the start of her turn if she has at least 1 hit point and isn't in sunlight or running water. If Aurora takes radiant damage or damage from holy water, this trait doesn't function at the start of her next turn."

- name: "Spider Climb"
  desc: "Aurora can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."

- name: "Vampiric Bite"
  desc: "Aurora's fanged bite deals 1d6 piercing damage plus 1d6 necrotic damage, and she regains hit points equal to the necrotic damage dealt. This attack can only be used on a willing creature, a creature that is grappled by her, incapacitated, or restrained."

- name: "Bardic Inspiration (d8)"
  desc: "Aurora has five Bardic Inspiration dice per long rest. As a bonus action, a creature within 60 feet that can hear her gains an inspiration die (1d8) to add to one ability check, attack roll, or saving throw."


# SPELLS
spells:
  - Aurora is a 6th-level spellcaster. Her spellcasting ability is Charisma (spell save DC 15, +7 to hit with spell attacks). She knows the following bard spells:
  - Cantrips (at will): Minor Illusion, Vicious Mockery, Mage Hand, Blood Tendril*
  - 1st level (4 slots): Charm Person, Disguise Self, Healing Word, Blood Knife*
  - 2nd level (3 slots): Invisibility, Shatter, Mirror Image, Blood Whip*
  - 3rd level (3 slots): Hypnotic Pattern, Dispel Magic, Blood Barrier*


# ACTIONS
actions:
  - name: "Multiattack"
    desc: "Aurora makes two attacks with her Blood Knife."

  - name: "Blood Knife"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d4 + 3) piercing damage plus 5 (1d8) necrotic damage."

  - name: "Unsettling Words"
    desc: "As a bonus action, Aurora can expend one use of her Bardic Inspiration to choose one creature she can see within 60 feet. Roll the Bardic Inspiration die, and the creature must subtract the number rolled from the next saving throw it makes before the start of Aurora's next turn."


# BONUS ACTIONS
bonus_actions:
  - name: "Healing Bite (1/Day)"
    desc: "As a bonus action, Aurora can use her bite attack on a willing creature and heal it for 2d6 hit points. Aurora does not gain any hit points from this use of her bite."


# REACTIONS
reactions:
  - name: "Cutting Words"
    desc: "When a creature Aurora can see within 60 feet makes an attack roll, an ability check, or a damage roll, she can use her reaction to expend one use of Bardic Inspiration, roll the die, and subtract the number rolled from the creature's roll."

```