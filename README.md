# tr1ck_imgcls

Trick Image Classification

## Example

```bash
python3 tr1ck_imgcls.py --epsilon '0.1' --attack 'ifgsm' --image 'shark.png' --out 'none'
```

## Usage

```
--e/-e epsilon value 
--attack/-a attacktype['fgsm', 'ifgsm', 'mifgsm']
--image/-i imagepath
--out/-o output[allpngs,justmixed,none]
```
## Note
Noise for ifgsm_attack and mifgsm_attack not yet implemented on visual.

