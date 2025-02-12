# My QMK repo with miryoku layout

TODO:
 
- [ ] don't merge from miryoku - add layout and keyboards one by one!
- Lily58
    - [ ] map additional Lily58 keys? (https://www.reddit.com/r/olkb/comments/w8vky0/help_with_addiong_extra_keys_miryoku/)
- Plaid
    - [ ] find a good layout


## Lily58

```shell
$ CONVERT_TO=promicro_rp2040 qmk compile -c -kb lily58/rev1 -km manna-harbour_miryoku
$ cp lily58_rev1_manna-harbour_miryoku_promicro_rp2040.uf2 /Volumes/RPI-RP2
```
