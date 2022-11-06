- ## Workflow
	- **Log adventures in Journal** -> **Add Markers and TODO** -> **Convert TODO to pages/notes**
	- Using this setup for DND or any other role playing game is easy enough, during you adventures just log whatever is happening and be sure to make new blocks for each day (If possible with fantasy date, if not count up the days) and each location
	- When one of the tags below happen be sure to mark them and if possible create a unique name. This will give you a dedicated page to use a template in and an overview of all things related to that item/quest/person/location
	- Remember to use logseqs task management to mark anything you want to cleanup later. Getting an item? Just mark it #item and add TODO so you can later update your character sheet without disrupting the flow of the game.
- ## Quests
	- Any good adventure has quests, but sometimes you don't know if things are related. Be sure to sometimes go back through notes and add links to quest pages to create a red thread throughout your notes related to a quest.
- ## Tags
	- #npc - Meeting NPC for first time
	- #quest - Learning about a quest
	- #status - Effects happening
	- #item #item/get #item/lose
		- Receiving an item, use get and lose if you want to use the journal to know if you still have an item
	- #money
		- Mark down money switching hands
	- #location - Switching to a new location
- ## Page Templates
	- ### NPC Character
	  template:: NPC Character
	  template-including-parent:: false
	  collapsed:: true
		- type:: character
		  alias::
		  race:: 
		  class:: 
		  belief::   
		  hometown::
		  description::
		- ## Description
		- ## Goals
		- ## Relationships
	- ### Player Character
	  template:: Player Character
	  template-including-parent:: false
	  collapsed:: true
		- type:: character
		  alias::
		  player:: 
		  active:: true
		  race:: 
		  class:: 
		  belief::   
		  hometown::
		- ## Description
		- ## Goals
		- ## Relationships
	- ### Player
	  template:: Player
	  template-including-parent:: false
	  collapsed:: true
		- type:: player
		  character::
		  phone::
		  email::
		- ## Notes
	- ### Item
	  template:: Item
	  template-including-parent:: false
	  collapsed:: true
		- type:: item
		  magic:: false
		  worth:: 1gp
		  description::
		- ## Description
		-
	- ### Region
	  template:: Region
	  template-including-parent:: false
	  collapsed:: true
		- type:: region
		  description::
		  towns::
	- ### Town
	  template:: Town
	  template-including-parent:: false
	  collapsed:: true
		- type:: town
		  region::
		  size:: medium
		  description::
		- ## Description
		- ## People of note
		- ## Quests
		-
	- ### Location
	  template:: location
	  template-including-parent:: false
	  collapsed:: true
		- type:: location
		  town::
		  residents::
		  description::
		- ## Description
		- ## Residents
- ## Block Templates
	- ### Session
	  template:: session
	  template-including-parent:: false
		- ### Session
		  attending::
		  location::
		  start::
		  end::
	- ### Day
	  template:: day
	  template-including-parent:: false
		- ### Day
		  location::
		  season::
		  summary::
		-