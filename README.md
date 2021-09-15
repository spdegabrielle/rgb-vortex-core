# rgb-vortex-core
notes on RGB Vortex core keyboard

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

unclear what above line means

* Support time delay, press 15ms key (Fn + T) each time to delay 15ms, press 0.1s key (Fn + G) each time to delay 0.1s, press 0.5s key (Fn + B) each time to delay 0.5s. Consecutive delay will add up but will only be counted as 1 key stroke. Every key can program up to 32 key strokes.

* If there is no key pressed for 15 sec. in programming mode, it will back to normal mode.


## Restore to factory default:

Reset layer: Press and hold **Fn** + **R**, L_spacebar LED will be flashing in white color for 5 seconds, then the layer will restore to default.

Clear all layers: Press and hold both **Alt**, L_spacebar LED will be flashing in white color for 5 seconds it will clean all layers’ key codes if you had programmed. (return to default layer.)


## Backlight effects

Backlight effects are set on a per layer basis; L0 can have a different effect to L1 etc.

Hold Pn

Tap R while holding Pn to cycle through single colour backlight effects
* Tap Q, W, or E while holding Pn to select red, green or blue as colour for single colour backlight effect.

Tap T while holding Pn to cycle through multi-colour backlight effects




----
relevant notes

http://vortexgear.tw/db/upload/webdata4/vortex_20198523345811246.pdf

https://www.vortexkeyboard.com.tw/

https://www.vortexkeyboard.com.tw/m/2001-1796-22734,c1409-1.php?Lang=en

https://www.vortexkeyboard.com.tw/ezfiles/796/1796/img/981/RGBCOREusermanual.pdf

https://sevenseacat.net/posts/2017/the-noobs-guide-to-programming-a-vortex-core/

https://www.mechtype.com/vortex-core-review/345


https://spotonpccases.co.uk/my-account/

