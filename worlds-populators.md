# ð ä¸ççæå¨

### ä¸¤ä¸ªçæå¨æ å­

```yaml
worlds_populators:
  custom_block:
    block: myitems:custom_block
    worlds:
    - world
    replaceable_blocks:
    - STONE
    - DIRT
    - ANDESITE
    - GRANITE
    - COBBLESTONE
    - GRAVEL
    biomes:
    - PLAINS
    chunk_chance: 70.0
    max_height: 45
    min_height: 25
    vein_blocks: 6
    chunk_veins: 1
  custom_block_2:
    block: myitems:custom_block_2
    worlds:
    - world
    replaceable_blocks:
    - DIRT
    chunk_chance: 100.0
    max_height: 64
    min_height: 40
    vein_blocks: 3
    chunk_veins: 1
```

è¯¥ç¤ºä¾éç½®æå®ä¸ççæå¨ï¼å¨ **world** ä¸çä¸­çæèªå®ä¹æ¹å **"myitems:custom\_block"** å¹¶åªå¨çç©ç¾¤ç³» `PLAINSï¼å¹³åï¼` ä¸­å¯¹ç±»åä¸º STONE, DIRT, ANDESITE, GRANITE, COBBLESTONE, GRAVEL çæ¹åè¿è¡æ¿æ¢.
ä¸å°å¨æ¯ä¸ªåºåä¸­çæ 1 ä¸ªç± 3 ä¸ªèªå®ä¹æ¹åç»æçç¿è.


### vein\_blocks, chunk\_veins, chunk\_chance

{% hint style="warning" %}
ä¸è¦è®¾ç½®è¿é«çæ°å¼ï¼å¦åä¼å¯¼è´æå¡å¨æ»åäº§çå¤§éå»¶è¿.\
ä½ å¯ä»¥åè Itemsadder æä»¶å¤¹ä¸ `blocks.yml` æä»¶åçæ°å¼.
{% endhint %}

**chunk\_veins**: åºåä¸­çæçç¿èæ°é\
**vein\_blocks**: æ¯ä¸ªç¿èä¸­çèªå®ä¹æ¹åæ°éï¼æ**ç¿èå¤§å°**ï¼\
**chunk\_chance**: åºåä¸­çæèªå®ä¹ç¿ç©çå ç. ï¼è¶ç¨æçç¿ç³è®¾ç½®çæ°å¼è¶ä½ï¼\

{% hint style="warning" %}
<mark style="color:red;">**æ§ç ItemsAdder**</mark> **3.1.6** ä¹åççæ¬ä½¿ç¨ä¸åå±æ§ä»£æ¿ï¼\
`chunk_veins` -> `iterations`

`vein_blocks` -> `amount`

`chunk_chance` -> `chance`
{% endhint %}

### Biomes

ä½ å¯ä»¥ç§»é¤è¯¥éé¡¹ï¼æä»¶ä¼å¨æ¯ä¸ªç¾¤ç³»é½çæèªå®ä¹æ¹å

```yaml
  custom_block:
    block: myitems:custom_block
    worlds:
    - world
    replaceable_blocks:
    - STONE
    - DIRT
    - ANDESITE
    - GRANITE
    - COBBLESTONE
    - GRAVEL
    chunk_chance: 70.0
    max_height: 45
    min_height: 25
    vein_blocks: 6
    chunk_veins: 1
```

### å¯æ¿æ¢çæ¹åï¼replaceable_blocksï¼

ä½ å¯ä»¥ç§»é¤è¯¥éé¡¹ï¼æä»¶ä¼çæç¿ç³æ¥æ¿æ¢æ¯ä¸ªèªå®ä¹æ¹åï¼èä¸æ¯æ£æ¥æ¯å¦å¯ä»¥æ¿æ¢

```yaml
  custom_block:
    block: myitems:custom_block
    worlds:
    - world
    chunk_chance: 70.0
    max_height: 45
    min_height: 25
    vein_blocks: 6
    chunk_veins: 1
```

