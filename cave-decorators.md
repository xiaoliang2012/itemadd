# ðª¨ æ´ç©´çæå¨

## çææ´ç©´è£é¥°ç©

{% hint style="warning" %}
çæ¬éæ±ï¼ **ItemsAdder** 3.1.6+
{% endhint %}

ä½¿ç¨ ItemsAdder ç **æ´ç©´çæå¨**ï¼ä½ å¯ä»¥å¨ä¸ççæ´ç©´ä¸­çæè£é¥°ç©ï¼ä½¿å¾æå¡å¨çèµ·æ¥æ´å ä¸ä¸ï¼æ´æç¹è².\

ä¾å¦ï¼å¯ä»¥å¶ä½æ°çèèãå°æ¤ç©ãå°ç³ååä»»ä½è£é¥°

![](<../../.gitbook/assets/image (81).png>)

## åå»ºä¸ä¸ªæ´ç©´çæå¨

### åå»ºéç½®æä»¶

ç°å¨è®©æä»¬æ¥å¶ä½å°å¨ä¸çåå¤çæçå°ç³å

```yaml
info:
  namespace: myitems
cave_decorators:
  small_rocks:
    block: small_rocks
    bottom_blocks:
    - DIRT
    - GRASS_BLOCK
    - STONE
    - COBBLESTONE
    - MOSSY_COBBLESTONE
    biomes:
    - PLAINS
    - SUNFLOWER_PLAINS
    - RIVER
    - MOUNTAINS
    - MOUNTAIN_EDGE
    - BIRCH_FOREST
    - BIRCH_FOREST_HILLS
    - TALL_BIRCH_FOREST
    - TALL_BIRCH_HILLS
    worlds:
      - world
    chance: 100
    max_height: 255 
    min_height: 0
    amount: 4
    position: SURFACE
```

å±æ§è¯¦æï¼

`block` ä¸º çæçèªå®ä¹æ¹å

`bottom_blocks` ä¸º å³å®æ¯å¦è½çæèªå®ä¹æ¹åçæ¹åç±»åï¼èªå®ä¹æ¹åå°ä¼å¨è¯¥å±æ§è®¾ç½®çæ¹åç±»åä¸çæï¼

`biomes` ä¸º åè®¸çæççç©ç¾¤ç³»

`worlds` ä¸º åè®¸çæçä¸ç

`chance` ä¸º æ¯ä¸ªåºåä¸­çæçå ç

`max_height` ä¸º åè®¸çæçæå¤§é«åº¦

`min_height` ä¸º åè®¸çæçæå°é«åº¦

`amount` ä¸º ä»è£é¥°ç»ï¼surface_decoratorsï¼ä¸­çæçèªå®ä¹æ¹åæ°é,ï¼ä¾å¦ï¼ä½ å°è¯¥å±æ§è®¾ç½®ä¸º 5,å¨çæè¯¥èªå®ä¹æ¹åæ¶ä¼çæ 5 ä¸ªè¿å¨ä¸èµ·çèªå®ä¹æ¹åï¼

`position` ä¸º æå®èªå®ä¹æ¹åçæçä½ç½®ï¼ç±»åæï¼`SURFACE` å `CEILING`.

## åå»ºèªå®ä¹æ¹å

ç°å¨ä½ åªéè¦æ ¹æ®ä¸åæç¨åå»ºèªå®ä¹æ¹å.\
å¹¶å³å®ä½¿ç¨ä¸åæä¸ä¸ªç±»åæ¥åå»ºèªå®ä¹æ¹åï¼ 
<br>`REAL_NOTE`, `REAL_WIRE`ï¼ `REAL_TRANSPARENT` ï¼`REAL` ï¼æ ¹æ®å·ä½éæ±æ¥éæ©ç±»åï¼
{% content-ref url="creating-a-custom-item/blocks/block.md" %}
[block.md](creating-a-custom-item/blocks/block.md)
{% endcontent-ref %}
