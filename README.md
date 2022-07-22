# Convert sprite animation from .ssbp to .gif

### based on /galaxy18/ssbp_saomd

## \*\* ONLY Supports SpriteStudio5 DATA_VERSION 3 .ssbp files \*\*

## Known Issues
- Vertex Transforms are not performed(can cause parts overlapping and incorrect sizing/positioning)
- Weapons and other Option parts/animations(Capes, Tails, Effects) are not drawn together

## Requirements
- [Python 3.8+](https://www.python.org/getit/)
- [Google Chrome](https://www.google.com/chrome/)

## How To Use
```
python convertSSBP.py sample/ch00_40_Elm_M_Normal_TransBattle/ch00_40_Elm_M_Normal_TransBattle.ssbp
python -m http.server 8081
```
Open [this](http://localhost:8081/SpriteAssembler.html) in Google Chrome and select pose to view.

## Not Implemented
- Label Data is not retrieved
- Effect Data is not retrieved
