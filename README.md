# QWERTY for French
#### Keyboard layout for people writing French frequently on a QWERTY International Mac keyboard (ISO).

This keyboard layout makes à é è, ç, œ, ù, ï (+caps) and · (median point useful for inclusive new french forms) more easily accessible on a QWERTY International Mac physical keyboard.

I adapted to it in a couple of hours and now find it much more enjoyable when writing in French than the standard QWERTY  layouts offered on Mac OS.

## Why?

I like the standard QWERTY International Mac keyboard much more than the current AZERTY keyboard. 

(The main reason is that the current AZERTY layout hides many of the 'programming characters' like \ or [], that were selected because they were directly accessible on QWERTY keyboards. The other reason is that the organization of accented characters is not even good on AZERTY)

At the same time, I felt that there could be a more direct way to use French specific characters than deadkeys.

Of course the QWERTY International layout must serve many languages, but there is a place for a layout fine tuned for people who write in English and French.


## Manual installation

1.  Drop the `FrenchQwerty.bundle` file into your `~/Library/Keyboard Layouts` directory.
2.  **Important:** Run the following command in your Terminal to clear the keyboard layout cache. This ensures that macOS recognizes the new layout.
    ```
    sudo rm /System/Library/Caches/com.apple.IntlDataCache.le*
    ```
3.  Restart your computer.
4.  After restarting, go to **System Settings > Keyboard > Input Sources**, click the **+** button, and you should now find **French-QWERTY** in the list.

## Selecting the layout 

The layout will be found in the Others section, at the bottom of the language list.

 <img width="947" alt="Capture d’écran 2024-07-01 à 19 55 41" src="https://github.com/juliendorra/QWERTY-for-French/assets/109677/0a373582-390c-4107-ab52-85359a5f8c56">

 ### You can now use:
 
 - [option] + [a], [e], [~ `] ===> à, é, è
 - [option] +  [o] ===> œ
 - [option] +  [u] ===> ù 
 - [option] +  [i] ===> ï
 - [option] +  [c] ===> ç

+ [Shift/Caps] or [Caps Lock] will give you the capitalized accented character. Always use accented caps! They help reading and avoiding confusion.

 - [option] + [^ 6] works as a deadkey and can be applied to û and ô

 - use [option] + [Shift/Caps] + [> .] to get · (the median point). Useful for example when you want to be inclusive of genders yet effective: « Message aux étudiant·e·s »


*QWERTY for French was created thanks to Ukulele: https://software.sil.org/ukelele/*

QWERTY for French layout was tested on both US QWERTY Macbook keyboards and QWERTY International Macbook keyboards.

 ### Alternatives
 
 **Qwerty-Lafayette**
 Use an universal deadkey to access all accented characters
 https://qwerty-lafayette.org/
 
 **Qwerty-fr**
https://qwerty-fr.org
 

