# Kannada Keyboard Layout for OSX

- Feb 8, 2020
- Version 2
- Thamme Gowda

This repository contains a keyboard layout for OSX. It is an XML config file that maps QWERTY keys to Kannada Unicode codepoints. (no extra black-magic)

## Installation
(Tested on OSX 10.15)
1. Download `Kannada-TGv1.keylayout` from this repository and place it in either one of the two paths: `~/Library/Keyboard\ Layouts` or `/Library/Keyboard\ Layouts/`, but not both.
2. System Preferences > Keyboard > Input Sources > (Click `+` on the bottom left ) > (search Kannada-TGv2) and add. Also check "Show input menu in menu bar"

3. An icon - either a keyboard or US flag - should appear next to the clock widget in the System menu bar on top. Select Kannada-TGv2. Start typing

## WARNING
1. Turning capslock ON retains English, so use capslock to quickly switch to/from english/latin alphabet. Note that turning the Capslock ON submits lowercase latin alphabet, however, Shift+Key to input upper case letters.
2. Turn Capslock OFF to enable Kannada mode.
3. CMD+C, CMD+V etc system shortcuts should continue to work. However, CTRL, SHIFT, OPTION keybindings might break.

## QWERTY maps to Kannada
ಅ a
ಅ A = SHFT+a
ಇ i
ಈ I
ಉ u
ಊ U
ಋ R
ಎ e
ಏ E
ಐ f
ಒ o
ಒ O
ಔ F
ಅಂ aM
ಅಃ aH

ಕ k
ಖ K
ಗ g
ಘ G
ಙ z

ಚ c
ಛ C
ಜ j
ಝ J
ಞ Z

ಟ q (because t is taken by ತ)
ಠ Q
ಡ w (because d is taken by ದ)
ಢ w
ಣ N

ತ t
ಥ T
ದ d
ಧ D
ನ n

ಪ p  
ಫ P
ಬ b
ಭ B
ಮ m

ಯ y
ರ r
ಲ l
ವ v
ಶ x
ಷ X
ಸ s
ಹ h
ಳ L

೧   ⌥ + 1
೨   ⌥ + 2
೩   ⌥ + 3
೪   ⌥ + 4
೫   ⌥ + 5
೬   ⌥ + 6
೭   ⌥ + 7
೮   ⌥ + 8
೯   ⌥ + 9
೦   ⌥ + 0

## ಕಾಗುಣಿತ
TLDR; Use Hold OPTION(⌥) key and press vowel to get the corresponding vowel modifier. Capital letter means hold SHIFT key.
ಕ  k    -- (unicode adds ಅ as the default vowel to all consonants)
ಕ್  ಕ + a -- (removes the default ಅ vowel)
ಕಾ k ⌥+A    = k SHIFT+OPTION+a
ಕಿ k ⌥+i
ಕೀ k ⌥+I
ಕು k ⌥+u
ಕೂ k ⌥+U
ಕೃ  k ⌥+R
ಕೆ  k ⌥+e
ಕೇ k ⌥+E
ಕೈ k ⌥+f
ಕೊ  k ⌥+o
ಕೋ k ⌥+O
ಕೌ k ⌥+F
ಕಂ  k M  == k OPTION+`
ಕಃ  k H == k OPTION+SHIFT+`

## ಅರ್ಧಾಕ್ಷರ
TLDR; While holding OPTION before vowel gives vowel modifier as seen in previous section, pressing OPTION before a consonant takes out default vowel.
For example:
ಕ್ ⌥+k == k ⌥+A
ಖ್ ⌥+K == K ⌥+A
ಅರ್ಧಾಕ್ಷರ = a ⌥+r D ⌥+A ⌥+k X r

## Credits:
The keyboard mapping was done by using http://software.sil.org/ukelele/. So thanks to the developer(s) of this tool.

## License
Use it for whatever you want to type. However, the developer/author provide no guarantee on service and hold no responsibility for any damage. Therefore use this at your own risk.
