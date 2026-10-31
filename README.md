# A-Short-Hike-VR
VR Mod for A Short Hike

<img width="1024" height="1536" alt="A Short HikeVR" src="https://github.com/user-attachments/assets/1cef35ff-dc10-4bec-a2b3-195d18d69d78" />


A SHORT HIKE VR  -  VR mod for "A Short Hike" (Unity 2019.4, Mono x86 / 32-bit, built-in renderer, BepInEx 5)
==============================================================================================================
Version 0.1.4 (test on Quest 3 Steam,Epic and GOG)

IMPORTANT: this mod uses **STEAMVR** (OpenVR)

INSTALL
-
  1. unzip into the game folder.
  2. Start SteamVR, then the game. If the headset stays black: start the game with -force-d3d11.
  
VIEW
-
  * THIRD PERSON: you stand where the game camera is and look around with your head. Your view does
    not swing with the game camera (only when it jumps to a new shot); VR menu "turn with the game camera" = on
    makes it follow all the time.
    VR menu (third person): "right stick" = GameCamera (turns the game camera, as in the game) or TurnView (turns
    YOU, snap / smooth like first person); "height" (up / down) and "forward / back" (closer to / further from
    Claire) move your place from the game camera. Config: [View] ThirdPersonRightStick / ThirdPersonHeight /
    ThirdPersonForward.
  * FIRST PERSON: CLICK THE RIGHT STICK (R3) to switch. You are Claire's eyes (her model hidden - VR menu:
    HeadOnly = only the head hidden, you see your body), you walk
    where you look, the right stick turns you (snap 30 degrees or smooth - VR menu). Click again = third person.
  * Menus / pause: the game's picture on a screen in front of you. In play the game's text / HUD floats on a
    see-through screen.

CONTROLS (the VR controllers are a gamepad for the game - its own pad controls and button pictures)
-
  Left stick ............ move 
  
  Right stick ......... third person: camera / first person: turn
  
  A / B (right) ......... A / B 
  
  X / Y (left) ........ X / Y
  
  Right / left trigger .. RT / LT
  
  Right / left grip ... RB / LB
  Left stick click ...... L3
  
  Right stick click ... FIRST / THIRD PERSON (in play)
  
  X + Y together ........ START (pause menu)
  
  A + B together ...... BACK
  
  Both stick clicks: tap = re-centre the view
  
  Both stick hold 1.2 s = VR settings menu.
  
  Upside down picture: VR menu "Headset picture upside down fix" / "Screen picture upside down fix".

CHANGES
  0.1.4  
  * Missing water, for real this time: the sea is a small plane the game moves to wherever the CENTRE of
         its narrow camera view hits the water - fine for the flat game, but in VR you look other ways with a
         much wider view, so its edges showed (and it froze while the view centre missed the water). It now stays
         under your head and is big enough to reach the horizon all round.
  
  * Third person options: right stick turns your view (TurnView) or the game camera; your height and
         forward / back place, all in the VR menu (live).
  
  * First version: SteamVR stereo view for the 32-bit game, third person at the game camera, first person
         toggle on the right stick click, the controllers as a gamepad (InControl), screen for menus / HUD.
