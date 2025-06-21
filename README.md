# keyman-ports
This repository has the keyboard layouts I created for Linux in XKB, which I ported for Keyman to make them cross-platform compatible.
## How to use
1. [Download and set up Keyman](https://keyman.com/) for your operating system.
2. Download the `.zip` file of the desired keyboard layout from this repository. Extract it.
3. Double-click the compiled `.kmx` file and install it in Keyman.
4. Enjoy typing..!
## Details of the layouts
### 1. Devanagari KaGaPa Phonetic
This layout is the KaGaPa phonetic layout for the Devanagari script, as distributed in Linux. This is a very intuitively designed layout, strictly following recommendations and key combinations as stated by Unicode, hence a well-compliant one.
### _Keymap_
#### Normal
![DeKaGaPa](https://github.com/user-attachments/assets/5bb81590-ba77-41e1-93bf-869dabe353c0)

#### Shift
![DeKaGaPaShft](https://github.com/user-attachments/assets/66cf585e-3753-4557-aef9-2be29cbe3e65)

#### RAlt
![DeKaGaPaAltGr](https://github.com/user-attachments/assets/354ef313-7739-4914-8aa5-593c11b9651f)

#### Shift + RAlt
![DeKaGaPaShftAltGr](https://github.com/user-attachments/assets/a2cef40d-d05c-45f7-a93d-987bd3270e86)

### 2. Modi KaGaPa Phonetic
This layout is the KaGaPa phonetic layout for a historically important script, called 'Modi'. It was prominently used to write Marathi, and in a few instances, for Hindi and Sanskrit. It is phonetically equivalent to Devanagari KaGaPa Phonetic, i.e., using similar character mapping, but for Modi letters.
### _Keymap_
#### Normal
![MoKaGaPa](https://github.com/user-attachments/assets/1cea2c6e-54bf-49d3-bfab-928881d2032d)

#### Shift
![MoKaGaPaShft](https://github.com/user-attachments/assets/d8d2cc14-d758-44c9-a7ae-38374e7a8397)

#### RAlt
![MoKaGaPaAltGr](https://github.com/user-attachments/assets/ab721814-bfac-4261-9a0c-c2995091ce9d)

#### Shift + RAlt
![MoKaGaPaShftAltGr](https://github.com/user-attachments/assets/d9d5ec58-4a13-472d-8d27-9bf3cbd19283)

### 3. Vedic Symbols
This layout is designed to type all the Vedic Symbols included in the `Devanagari Extended` and `Vedic Extensions` Unicode blocks. This layout is designed in such a way, that the places of symbols can be logically correlated while typing, making it easy to type them.
### _Keymap_
#### Normal
![VSymbols](https://github.com/user-attachments/assets/014817e8-7bdb-44ae-88b1-20eeceb9e0ea)

#### Shift
![VSymbolsShft](https://github.com/user-attachments/assets/4e678e19-3d10-4a28-bd23-6b1e68620da5)

#### Shift + RAlt
![VSymbolsShftAltGr](https://github.com/user-attachments/assets/e5e40508-346f-47c6-a6a0-be90ca8b2f29)

## Modifying/Customising
Use [Keyman Developer](https://keyman.com/developer/) to customise these layouts.

## Changing Languages
As these keyboard layouts are not being distributed via a package (`.kmp` file), they are added under the default language, i.e., English, after installation. To change the language of a keyboard layout, use the `Add/remove languages` option in Keyman configuration for that particular layout.

## License
These layouts are distributed under the [MIT License](https://opensource.org/license/mit).
