TAGS REFERENCE
This system is using PHP TWIG to render the templates and most of the functionality of TWIG, is available to you to play around with.

VARIABLE LIST
{% if variables.name is defined %} {{ variables.name }} {% endif %}

{% if variables.challenge_rating is defined %} {{ variables.challenge_rating }} {% endif %}

{% if variables.types is defined %} {{ variables.types }} {% endif %}

{% if variables.size is defined %} {{ variables.size }} {% endif %}

{% if variables.languages is defined %} {{ variables.languages }} {% endif %}

{% if variables.alignment is defined %} {{ variables.alignment }} {% endif %}

{% if variables.description is defined %} {{ variables.description }} {% endif %}

{% if variables.suggested_environments is defined %} {{ variables.suggested_environments }} {% endif %}

{% if variables.armor_class is defined %} {{ variables.armor_class }} {% endif %}

{% if variables.hit_points is defined %} {{ variables.hit_points }} {% endif %}

{% if variables.strength is defined %} {{ variables.strength }} {% endif %}

{% if variables.dexterity is defined %} {{ variables.dexterity }} {% endif %}

{% if variables.constitution is defined %} {{ variables.constitution }} {% endif %}

{% if variables.intelligence is defined %} {{ variables.intelligence }} {% endif %}

{% if variables.wisdom is defined %} {{ variables.wisdom }} {% endif %}

{% if variables.charisma is defined %} {{ variables.charisma }} {% endif %}

{% if variables.base_movement_in_ft is defined %} {{ variables.base_movement_in_ft }} {% endif %}

{% if variables.fly_movement_in_ft is defined %} {{ variables.fly_movement_in_ft }} {% endif %}

{% if variables.hover_movement_in_ft is defined %} {{ variables.hover_movement_in_ft }} {% endif %}

{% if variables.burrow_movement_in_ft is defined %} {{ variables.burrow_movement_in_ft }} {% endif %}

{% if variables.swim_movement_in_ft is defined %} {{ variables.swim_movement_in_ft }} {% endif %}

{% if variables.climb_movement_in_ft is defined %} {{ variables.climb_movement_in_ft }} {% endif %}

{% if variables.senses is defined %} {{ variables.senses }} {% endif %}

{% if variables.skills is defined %} {{ variables.skills }} {% endif %}

{% if variables.saving_throws is defined %} {{ variables.saving_throws }} {% endif %}

{% if variables.damage_vulnerabilities is defined %} {{ variables.damage_vulnerabilities }} {% endif %}

{% if variables.damage_resistances is defined %} {{ variables.damage_resistances }} {% endif %}

{% if variables.damage_immunities is defined %} {{ variables.damage_immunities }} {% endif %}

{% if variables.condition_immunities is defined %} {{ variables.condition_immunities }} {% endif %}

{% if variables.spellcasting is defined %} {{ variables.spellcasting }} {% endif %}

{% if variables.cast_at_will is defined %} {{ variables.cast_at_will }} {% endif %}

{% if variables.cast_one_per_day is defined %} {{ variables.cast_one_per_day }} {% endif %}

{% if variables.cast_twice_per_day is defined %} {{ variables.cast_twice_per_day }} {% endif %}

{% if variables.cast_thrice_per_day is defined %} {{ variables.cast_thrice_per_day }} {% endif %}

{% if variables.special_abilities is defined %} {{ variables.special_abilities }} {% endif %}

{% if variables.actions is defined %} {{ variables.actions }} {% endif %}

{% if variables.reactions is defined %} {{ variables.reactions }} {% endif %}

{% if variables.legendary_actions is defined %} {{ variables.legendary_actions }} {% endif %}

{% if variables.lair_description is defined %} {{ variables.lair_description }} {% endif %}

{% if variables.lair_actions is defined %} {{ variables.lair_actions }} {% endif %}

{% if variables.regional_effects is defined %} {{ variables.regional_effects }} {% endif %}

{% if variables.image_gallery_id is defined %} {{ variables.image_gallery_id }} {% endif %}

{% if variables.proficiency_bonus is defined %} {{ variables.proficiency_bonus }} {% endif %}

{% if variables.level is defined %} {{ variables.level }} {% endif %}

{% if variables.armor_proficiency is defined %} {{ variables.armor_proficiency }} {% endif %}

{% if variables.weapon_proficiency is defined %} {{ variables.weapon_proficiency }} {% endif %}

{% if variables.tools_proficiency is defined %} {{ variables.tools_proficiency }} {% endif %}

{% if variables.morale is defined %} {{ variables.morale }} {% endif %}

{% if variables.equipment is defined %} {{ variables.equipment }} {% endif %}

{% if variables.special_equipment is defined %} {{ variables.special_equipment }} {% endif %}

{% if variables.paragon_actions is defined %} {{ variables.paragon_actions }} {% endif %}

AVAILABLE FILTERS
|ParseTable Parses the Content as a table.

|ParseTableRandom Parses the Content as a random table.

|ParseList Parses the Content as a List.

CODE EXAMPLES
RENDERING AN IMAGE
Considering the part is called "imagePart" and you want no link to the image to appear.

{% if variables.image is defined %}
[img:{{ variables.imagePart }}|nolink] 
{% endif %}

SETTING A VARIABLE
{% set count = 1 %}

CONDITIONAL
{# If the variable exists #}
{% if variables.name is defined %} 
{# Your TWIG/HTML Code here #}
{% endif %}

LOOP
{# Define an array #}
{% set fruits = ['apple','peach','pear'] %}
{% for fruit in fruits %}
{# Your TWIG/HTML Code here #}
{{ fruit }}
{% endfor %}
