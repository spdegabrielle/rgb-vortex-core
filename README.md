# rgb-vortex-core
notes on RGB Vortex core keyboard

I had a lot of trouble understanding the official guide at https://www.vortexkeyboard.com.tw/ezfiles/796/1796/img/981/RGBCOREusermanual.pdf

These are my notes that decode most of the manual. Some mysteries still remain. Contributions and comments welcome.

### Basics

* Holding **Fn1** lets you type red glyphs
* Holding **Fn1+shift** lets you type green glyphs
* Holding **Fn** lets you type blue glyph actions

Layers are indicated by red, green and blue LED below the left spacebar, but layers don't have any relationship to the glyphs on the keys.



## Layers selection

If you select a layer a key will perform its programmed action if set. If it has not been programmed it will perform it's default action.

e.g. 'v' will still emit 'v' when L2 is selected if it has not been programmed.

* **Fn**+**M** = Default layer L0 (Spacebar left LED off)
* **Fn**+**<,** = Layer 1 L1 (Spacebar left LED showing Red color)
* **Fn**+**>.** = Layer 2 L2 (Spacebar left LED showing Green color)
* **Fn**+**Shift** = Layer 3 L3 (Spacebar left LED showing Blue color)
(layer selection happens when you release the keys)

## Key code Programming Instruction:

The default layer (L0) can not be programmed. Only layer 1(L1) ~ layer 3(L3) can be.

1. **Fn** and layer selector key (L1~L3) to select which layer you want to programmed.
2. **Fn** + **R_Ctrl** to enter the programming mode (R_Spacebar LED steadily lit in Blue color)
3. Press key to program (R_Spacebar LED flashing in Red color)
4. Key in the macro
5. Press **Pn** to finish (R_Spacebar LED back to Blue color again)
6. Press **Fn** + **R_Ctrl** to exit programming mode (Spacebar right LED off) 

**R_ctrl**, **M**, **<** , **>** and **L_Shift** keys are fixed can not be programmed.

You can repeat steps 2 to 5 to program multiple keys in a single session.


### More:

> * Support Fn layer (e.g., Fn + A) to program.

Fn+A is rewind, S is play/pause and D is fastforward. 

Does this mean that on programmable layers L1-L3 macros can be attached to these keys?


> * Support time delay, press 15ms key (Fn + T) each time to delay 15ms, press 0.1s key (Fn + G) each time to delay 0.1s, press 0.5s key (Fn + B) each time to delay 0.5s. 

Not tried this be seems clear that you can add multiple time delays to a macro.

> * Consecutive delay will add up but will only be counted as 1 key stroke. 
> * Every key can program up to 32 key strokes.


> * If there is no key pressed for 15 sec. in programming mode, it will back to normal mode.

It times out. This has happened to me a lot.


## Reset layers

Reset layer: Press and hold **Fn** + **R**, L_spacebar LED will be flashing in white color for 5 seconds, then the layer will restore to default.

Clear all layers: Press and hold both **Alt**, L_spacebar LED will be flashing in white color for 5 seconds it will clean all layers’ key codes if you had programmed. (return to default layer.)

NB: you may not be able to do these actions if you have remapped the relevant keys. Use factory reset by usinn the (windows only) firmware update tool.

## Factory reset

A factory reset can be achieved by reinstalling the firmware using the firmware installer tool found at https://www.vortexkeyboard.com.tw/m/2001-1796-22734,c1409-1.php?Lang=en

Direct link https://www.vortexkeyboard.com.tw/ezfiles/796/1796/img/981/RGBCOREFirmwareV1.04.05.exe  (windows only)


## Backlight effects

Backlight effects are set on a per layer basis; L0 can have a different effect to L1 etc.

1. Hold **Pn** 
2. Tap R while holding **Pn** to cycle through single colour backlight effects
3. Tap Q, W, or E while holding **Pn** to mix red, green or blue as colour for single colour backlight effect.

Tap T while holding **Pn** to cycle through multi-colour backlight effects

**Pn** with a selector key is used to change mode, select colours etc.

----
### Colour selection 

You have two options, choose colour from keyboard palette with the esc key, or mix the red, gree and blue components manually

**Pn** + **ESC** Palette - use keyboard as a palette and select the required colour

The following cycle through 7 steps in each or red,green and blue
* **Pn** + **Q** Single Color - Red 
* **Pn** + **W** Single Color - Green
* **Pn** + **E** Single Color - Blue

----
### single color LED modes

**Pn** + **R** **Display single color LED mode**

Cycles through the following modes:
* Interactive mode, 
* Flash vortex mode, 
* Aurora mode

----
### Full color LED modes

**Pn** + **T** **Display full color LED mode**

Press to cycle through the following: 
* Full key light mode
* Breath mode, 
* Vortex mode, 
* Rain drop mode.

----
### Controls

* **Pn** + C Brightness down
* **Pn** + V Brightness up - **BUG** does not go back to full brightness
* **Pn** + < Light effect speed down > Light effect speed up

### To be confirmed: 

* **Pn** + U Custom LED mode 1
* **Pn** + I Custom LED mode 2




* **Pn** + O Display recording 1
* **Pn** + P Display recording 2


## Other description:

Not clear what this means?
> 1. L_Win + L_Alt + R_Spacebar = R_Shift, R_win , Menu(Pn) and R_Ctrl as arrow keys

----

### Switch Fn / Pn position: 

Fn or Pn key only can swap to L_Ctrl, L_Win, L_Alt, L_Spacebar, R_Alt

Hit Fn and L_Shift for 3 seconds, then select new Fn key location directly 

Change Pn: With the above step

----

> 3. Fn1+Z as symbol key between L-shift and Z for ISO version

Not clear what this means?


----
relevant notes

manual: https://www.vortexkeyboard.com.tw/ezfiles/796/1796/img/981/RGBCOREusermanual.pdf

manual: http://vortexgear.tw/db/upload/webdata4/vortex_20198523345811246.pdf

Manufacturer: https://www.vortexkeyboard.com.tw/  (also on facebook)

Product page: https://www.vortexkeyboard.com.tw/m/2001-1796-22734,c1409-1.php?Lang=en

A related guide for the non-rgb vortex core: https://sevenseacat.net/posts/2017/the-noobs-guide-to-programming-a-vortex-core/

A fairly detailed review of vortex core: https://www.mechtype.com/vortex-core-review/345


The UK reseller I purchased mine from: ttps://spotonpccases.co.uk/

