# Follow Music automations
A Home Assistant package that allows you to follow the music in your house. 

## how it works

## dependencies
* Precense module
* Occupancy sensors to know in which room the person is, this can be a -motionsensor-, -mobile location-, etc. 
* Speaker entities in rooms
## Configuration
|Placeholder| Description|
|--|--|
|```input_boolean.follow_music```| Boolean to turn on or off the follow music function. |
|```input_select.music_controller```|an selfmade input_select with all your musicplayers, to select one to control the rest|
# https://philhawthorne.com/making-music-follow-you-around-the-home-with-home-assistant-and-sonos/
## Usage

### Scripts
#### sonos_group_motion

#### sonos ungroup motion

### Automations

#### Join music

####

action: script.sonos_ungroup_motion
data_template:
  target_player: media_player.keuken