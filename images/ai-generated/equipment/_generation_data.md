# 装备生成任务数据汇总

## 命名规范
- 文件路径：`frontend/public/images/ai-generated/equipment/{quality}/{slot}/equip_{id}_{pinyin_name}.png`
- 命名格式：`equip_{id}_{pinyin_name}.png`
- pinyin_name 用英文拼音小写下划线连接

## 风格标签（追加到所有 prompt 末尾）
```
STYLE_BASE: Cyberpunk ancient Chinese mythology, Shan Hai Jing creatures, digital art, trending on ArtStation, concept art, intricate details, neon glow effects, mechanical augmentation, biopunk, dark futuristic atmosphere, volumetric lighting, 8k resolution
NEGATIVE: low quality, blurry, deformed, distorted, bad anatomy, watermark, text, signature, ugly, disfigured, extra limbs, fused fingers, poorly drawn, sketch, photorealistic, realistic photo, 3D render
SUFFIX: 256x256 transparent background, game item icon
```

## 品级辅助标签
- common: `simple construction, basic design, mass-produced`
- uncommon: `refined details, polished finish, steel alloy material`
- rare: `data-stream surface, cyan circuit patterns, holographic accents`
- epic: `spirit energy veins, glowing runes, mystical aura`
- legendary: `golden divine light, holy inscriptions, legendary craftsmanship`
- mythic: `primordial cosmic power, rainbow nebula aura, mythological craftsmanship`

---

## LEGACY 装备 (10001-10075) — 41 件

### 武器 weapon (6)
- 10001 数据匕首 (data_dagger) — common — short triangular blade made of compressed recycled data shards, faint glitching cyan data streams on blade, hilt wrapped in dirty gray cloth tape, dull chipped edge, gray steel with patches of rust
- 10002 量子短剑 (quantum_sword) — uncommon — semi-transparent blade with shimmering data streams, fox-fire pattern on crossguard, blade edges flicker between solid and holographic states, cyan and purple neon glow, hilt wrapped in violet leather with circuit patterns
- 10003 守卫巨锤 (guard_hammer) — rare — massive black alloy hammer head with red Chinese character engraved, reinforced steel pipe handle with grip tape, brutalist industrial design, weighty silhouette, dark steel with red glowing accent runes
- 10004 机械法杖 (mech_staff) — rare — polished steel tube shaft with engraved spell circuit lines, levitating rotating prism core at top, cold blue glow emanating from core, mechanical joints and brass fittings
- 10005 精金重剑 (adamant_sword) — epic — wide thick blade with golden rune channel along spine, golden sparks fly when swung, mythril alloy with iridescent purple-gold sheen, ornate crossguard with flame motifs, two-handed grip wrapped in dark leather
- 10006 混沌之刃 (chaos_blade) — legendary — jet-black blade body with orange and purple chaotic energy flowing along the edge, dark void cracks on blade surface, ornate hilt wrapped in golden dragon scales, ancient chaos runes carved on pommel, golden divine light

### 头部 head (5)
- 10011 数据头盔 (data_helm) — common — matte gray polycarbonate shell, cyan data sensor strip on forehead, low-profile form factor, simple mass-produced military design
- 10012 量子面甲 (quantum_helm) — uncommon — semi-transparent purple glass visor showing internal data flows, fine steel alloy frame with quantum stability runes engraved
- 10013 守卫战盔 (guard_helm) — rare — full-enclosure design with red eye visor, side earpiece modules, heavy industrial military aesthetic, red glowing accent lines, data-stream surface texture
- 10014 机械头盔 (mech_helm) — epic — integrated HUD and comm system, mechanical eye array on forehead with multiple lens modes, brass and steel mechanical parts, intricate cyber-biopunk details, spirit energy veins glowing on sides
- 10015 混沌王冠 (chaos_crown) — legendary — jet-black metal crown set with 6 irregular orange-purple chaos gems, ancient chaotic runes along the band, void energy tendrils rising from the gems, golden divine light

### 身体 body (5)
- 10021 数据护甲 (data_chest) — common — lightweight polycarbonate construction, small data display panel on chest showing wearer status, blue and gray color scheme
- 10022 量子胸甲 (quantum_chest) — uncommon — purple data streams flowing across surface, fine steel alloy flexible joint plates, quantum stability emblem on chest center
- 10023 守卫战甲 (guard_chest) — rare — heavy dark alloy chestplate with raised pauldrons, integrated gorget, industrial military aesthetic, red accent stripes, holographic unit insignia
- 10024 机械战甲 (mech_chest) — epic — multi-layer composite armor plates, mechanical core interface on chest, high-end cyborg standard, spirit energy veins glowing softly
- 10025 混沌战甲 (chaos_chest) — legendary — jet-black alloy body with chaotic energy veins, six orange-purple chaos gems embedded on chest, void cracks between armor plates, golden divine light

### 腿部 legs (5)
- 10031 数据护腿 (data_legs) — common — lightweight polycarbonate construction, blue and gray color scheme, simple mass-produced design
- 10032 量子腿甲 (quantum_legs) — uncommon — purple data streams flowing across surface, flexible joint plates, refined details, polished finish
- 10033 守卫腿甲 (guard_legs) — rare — heavy dark alloy leg armor, red accent stripes, industrial military aesthetic, data-stream surface texture
- 10034 机械腿甲 (mech_legs) — epic — multi-layer mechanical leg plates, brass and steel mechanical parts, knee joints with cyber-biopunk details
- 10035 混沌腿甲 (chaos_legs) — legendary — jet-black alloy with chaotic energy, void cracks between plates, golden divine light, ornate dragon scale pattern

### 手部 hands (5)
- 10041 数据手套 (data_gloves) — common — matte gray polycarbonate, cyan data sensor strips on fingers, simple military design
- 10042 量子手套 (quantum_gloves) — uncommon — purple data streams flowing, fine steel alloy, quantum stability runes on knuckles
- 10043 守卫手套 (guard_gloves) — rare — heavy dark alloy with red accent stripes, data-stream surface texture, finger armor plates
- 10044 机械手套 (mech_gloves) — epic — brass and steel mechanical parts, mechanical finger joints, cyber-biopunk details, spirit energy veins
- 10045 混沌手套 (chaos_gloves) — legendary — jet-black alloy with chaotic energy, void cracks, golden dragon scale pattern on back

### 足部 feet (5)
- 10051 数据战靴 (data_boots) — common — matte gray polycarbonate, cyan data sensor strips, simple military boots
- 10052 量子战靴 (quantum_boots) — uncommon — purple data streams, fine steel alloy, polished finish
- 10053 守卫战靴 (guard_boots) — rare — heavy dark alloy with red accent stripes, industrial military design, ankle protection
- 10054 机械战靴 (mech_boots) — epic — brass and steel mechanical parts, mechanical ankle joints, cyber-biopunk details
- 10055 混沌战靴 (chaos_boots) — legendary — jet-black alloy with chaotic energy, void cracks, golden dragon scale pattern

### 饰品1 accessory1 (5)
- 10061 数据护符 (data_amulet) — common — simple data talisman pendant on leather cord, cyan data sensor on pendant
- 10062 量子坠饰 (quantum_amulet) — uncommon — semi-transparent purple crystal pendant, fine steel alloy setting, quantum stability runes
- 10063 守卫徽章 (guard_badge) — rare — military guard badge with red accent, data-stream surface, unit insignia
- 10064 机械核心 (mech_core) — epic — mechanical core pendant with brass parts, pulsing energy veins, cyber-biopunk details
- 10065 混沌之眼 (chaos_eye) — legendary — glowing purple eye amulet with void tendrils, golden divine light, ancient chaos runes

### 饰品2 accessory2 (5)
- 10071 数据戒指 (data_ring) — common — simple data ring with cyan sensor strip
- 10072 量子指环 (quantum_ring) — uncommon — purple data streams flowing around ring, quantum stability runes
- 10073 守卫戒指 (guard_ring) — rare — military guard ring with red accent, data-stream surface
- 10074 机械环 (mech_ring) — epic — brass and steel mechanical ring, mechanical gear details, energy veins
- 10075 混沌印记 (chaos_mark) — legendary — jet-black ring with chaotic energy patterns, void tendrils, golden divine light

---

## COMMON 普通品级 (10100-10147) — 48 件

### 武器 weapon (6)
- 10100 训练用剑 (training_sword) — basic wooden practice sword with cloth-wrapped grip
- 10101 木弓 (wood_bow) — simple wooden longbow, hunter's bow
- 10102 短杖 (short_staff) — basic apprentice's short staff with small crystal tip
- 10103 铁锤 (iron_hammer) — blacksmith's small iron hammer with wooden handle
- 10104 皮鞭 (leather_whip) — herder's leather whip, braided leather
- 10105 短匕首 (short_dagger) — street thug's small knife, simple blade

### 头部 head (6)
- 10106 布帽 (cloth_cap) — plainest cloth cap
- 10107 头巾 (headscarf) — ranger's headscarf
- 10108 兜帽 (hood) — thief's hood, dark cloth
- 10109 皮帽 (leather_cap) — hunter's leather cap
- 10110 铁皮面具 (iron_mask) — temporary iron face mask
- 10111 竹笠 (bamboo_hat) — coastal bamboo conical hat

### 身体 body (6)
- 10112 布衣 (cloth_robe) — plainest cloth robe
- 10113 皮甲 (leather_vest) — hunter's leather armor
- 10114 战衣 (war_robe) — militia war robe
- 10115 制服 (uniform) — patrol uniform
- 10116 背心 (vest) — light vest
- 10117 粗布长袍 (coarse_robe) — apprentice mage robe

### 腿部 legs (6)
- 10118 布裤 (cloth_pants) — plainest cloth pants
- 10119 皮护腿 (leather_legs) — hunter's leather leg guards
- 10120 战裤 (war_pants) — militia war pants
- 10121 短裤 (short_pants) — light short pants
- 10122 粗布长裙 (coarse_skirt) — apprentice long skirt
- 10123 绑腿 (leg_wraps) — field leg wraps

### 手部 hands (6)
- 10124 布手套 (cloth_gloves) — plainest cloth gloves
- 10125 皮手套 (leather_gloves) — hunter's leather gloves
- 10126 护手 (hand_guard) — militia hand guard
- 10127 拳套 (fist_wraps) — fighter's fist wraps
- 10128 绷带 (bandages) — boxer's hand bandages
- 10129 麻布手套 (linen_gloves) — apprentice linen gloves

### 足部 feet (6)
- 10130 布鞋 (cloth_shoes) — plainest cloth shoes
- 10131 皮靴 (leather_boots) — hunter's leather boots
- 10132 战靴 (war_boots) — militia war boots
- 10133 凉鞋 (sandals) — southern sandals
- 10134 草鞋 (straw_shoes) — wandering monk straw shoes
- 10135 法靴 (mage_boots) — apprentice mage boots

### 饰品1 accessory1 (6)
- 10136 木坠 (wood_pendant) — wooden carved pendant on hemp cord
- 10137 皮绳吊坠 (leather_pendant) — leather cord with polished stone or bone piece
- 10138 玉佩 (jade_pendant) — small green jade plate with fortune character
- 10139 铜徽章 (copper_badge) — militia copper badge with unit number
- 10140 麻绳项链 (hemp_necklace) — hemp rope strung with polished stones or wooden beads
- 10141 狗牌 (dog_tag) — soldier's metal dog tag engraved with name and number

### 饰品2 accessory2 (6)
- 10142 木戒 (wood_ring) — wooden ring with carved patterns
- 10143 皮戒 (leather_ring) — braided leather strips into ring
- 10144 铜戒 (copper_ring) — copper band with small copper bead
- 10145 手镯 (copper_bangle) — open-style copper bangle
- 10146 木环 (wood_loop) — wooden ring carved with mountain or water patterns
- 10147 学徒指环 (apprentice_ring) — simple silver band engraved with apprentice spell patterns

---

## UNCOMMON 高级品级 (10150-10197) — 48 件

### 武器 weapon (6)
- 10150 幽冥短刃 (youming_dagger) — cold gray mithril alloy blade with serrated edge, ebony hilt wrapped in purple cord, purple glow trails on swing
- 10151 钢制长剑 (steel_longsword) — standard steel blade with clean edge, infantry regiment issue, group flower pattern on crossguard
- 10152 强化长弓 (reinforced_bow) — composite steel-wood body with reinforced fiberglass limbs
- 10153 秘银法杖 (mithril_staff) — mithril shaft with silver base set with purple amethyst
- 10154 中型战锤 (medium_hammer) — steel block hammer head, hardwood handle with steel core
- 10155 星辉飞镖 (starlight_dart) — three-bladed dart with luminous paint on edges

### 头部 head (6)
- 10156 钢盔 (steel_helm) — infantry steel helmet
- 10157 夜行兜帽 (shadow_hood) — stalker's headcover
- 10158 秘银头环 (mithril_circlet) — mage's head ring
- 10159 强化面甲 (reinforced_mask) — heavy face armor
- 10160 幽冥兜帽 (youming_hood) — nine-hell infused hood, purple dark gold
- 10161 星辉头环 (starlight_circlet) — night-traveler head ring

### 身体 body (6)
- 10162 幽冥胸甲 (youming_chest) — shadow assassin chest armor, purple dark
- 10163 钢制胸甲 (steel_chest) — infantry standard chestplate
- 10164 秘银法袍 (mithril_robe) — mage's robe
- 10165 夜行长袍 (shadow_robe) — stalker's robe
- 10166 强化战甲 (reinforced_chest) — heavy war armor
- 10167 影行战衣 (shadow_war_robe) — night-traveler war robe

### 腿部 legs (6)
- 10168 钢制腿甲 (steel_legs) — infantry standard leg armor
- 10169 强化腿甲 (reinforced_legs) — heavy leg armor
- 10170 夜行护腿 (shadow_legs) — stalker's leg guards
- 10171 秘银护腿 (mithril_legs) — mage's leg armor
- 10172 钢制战裤 (steel_pants) — melee combat pants
- 10173 影行绑腿 (shadow_wraps) — night-traveler leg wraps

### 手部 hands (6)
- 10174 幽冥手套 (youming_gloves) — shadow assassin gloves
- 10175 钢制手套 (steel_gloves) — infantry standard gloves
- 10176 强化护手 (reinforced_gauntlets) — heavy gauntlets
- 10177 秘银手套 (mithril_gloves) — mage's gloves
- 10178 夜行手套 (shadow_gloves) — stalker's gloves
- 10179 钢爪 (steel_claw) — melee steel claw

### 足部 feet (6)
- 10180 钢制战靴 (steel_boots) — infantry standard war boots
- 10181 强化战靴 (reinforced_boots) — heavy war boots
- 10182 夜行皮靴 (shadow_boots) — stalker's leather boots
- 10183 秘银法靴 (mithril_boots) — mage's boots
- 10184 钢制长靴 (steel_long_boots) — melee long boots
- 10185 轻量跑靴 (light_boots) — scout's running boots

### 饰品1 accessory1 (6)
- 10186 钢制项链 (steel_necklace) — steel necklace
- 10187 秘银吊坠 (mithril_pendant) — mage's pendant
- 10188 夜行坠饰 (shadow_pendant) — stalker's pendant
- 10189 强化徽章 (reinforced_badge) — officer's badge
- 10190 钢制护符 (steel_amulet) — melee amulet
- 10191 星辉吊坠 (starlight_pendant) — night-traveler pendant

### 饰品2 accessory2 (6)
- 10192 钢制指环 (steel_ring) — steel ring
- 10193 秘银戒指 (mithril_ring) — mage's ring
- 10194 夜行指环 (shadow_ring) — stalker's ring
- 10195 强化戒指 (reinforced_ring) — officer's ring
- 10196 钢制手镯 (steel_bracer) — melee bracer
- 10197 星辉指环 (starlight_ring) — night-traveler ring

---

## RARE 稀有品级 (10200-10239) — 40 件

### 武器 weapon (5)
- 10200 海皇长枪 (haihuang_spear) — East Sea spirit tide refined spear, deep blue coral inlay, sea wave pattern
- 10201 守卫巨剑 (guard_greatsword) — guard regiment standard greatsword, dark alloy, holographic unit insignia
- 10202 玄铁长弓 (xuantie_bow) — xuantie heavy bow, dark iron with reinforced limbs
- 10203 精金法杖 (adamant_staff) — mithril staff with engraved spell circuit lines, glowing runes
- 10204 熔岩战锤 (lava_hammer) — Great Wasteland lava war hammer, glowing magma runes

### 头部 head (5)
- 10205 守卫战盔 (guard_helm_r) — guard regiment helmet, dark alloy with red eye visor
- 10206 精金头盔 (adamant_helm) — mithril forged helmet with golden rune channel
- 10207 玄铁面甲 (xuantie_mask) — xuantie face armor, dark iron construction
- 10208 云母头环 (mica_circlet) — mica head ring, magical crystal pattern
- 10209 熔岩战盔 (lava_helm) — Great Wasteland lava helmet, glowing magma veins

### 身体 body (5)
- 10210 海皇鳞甲 (haihuang_chest) — East Sea sea king scale armor, deep blue with fish scale pattern
- 10211 守卫战甲 (guard_chest_r) — guard regiment war armor, dark alloy with red accent stripes
- 10212 精金战甲 (adamant_chest) — mithril forged war armor, golden iridescent sheen
- 10213 玄铁鳞甲 (xuantie_chest) — xuantie scale armor, dark iron with overlapping plates
- 10214 云母法袍 (mica_robe) — mica mage robe, magical crystal pattern

### 腿部 legs (5)
- 10215 海皇鳞腿 (haihuang_legs) — East Sea sea king scale legs, deep blue
- 10216 守卫腿甲 (guard_legs_r) — guard regiment leg armor
- 10217 精金腿甲 (adamant_legs) — mithril forged leg armor
- 10218 玄铁腿甲 (xuantie_legs) — xuantie leg armor
- 10219 云母护腿 (mica_legs) — mica leg armor

### 手部 hands (5)
- 10220 守卫手套 (guard_gloves_r) — guard regiment gloves
- 10221 精金护手 (adamant_gauntlets) — mithril forged gauntlets
- 10222 玄铁手套 (xuantie_gloves) — xuantie gloves
- 10223 云母手套 (mica_gloves) — mica gloves
- 10224 熔岩护手 (lava_gauntlets) — Great Wasteland lava gauntlets

### 足部 feet (5)
- 10225 守卫战靴 (guard_boots_r) — guard regiment war boots
- 10226 精金长靴 (adamant_boots) — mithril forged long boots
- 10227 玄铁战靴 (xuantie_boots) — xuantie war boots
- 10228 云母法靴 (mica_boots) — mica mage boots
- 10229 熔岩战靴 (lava_boots) — Great Wasteland lava war boots

### 饰品1 accessory1 (5)
- 10230 潮汐坠 (tide_pendant) — East Sea tide essence pendant
- 10231 守卫徽章 (guard_badge_r) — guard regiment badge
- 10232 精金坠饰 (adamant_pendant) — mithril pendant
- 10233 玄铁护符 (xuantie_amulet) — xuantie amulet
- 10234 云母吊坠 (mica_pendant) — mica pendant

### 饰品2 accessory2 (5)
- 10235 守卫戒指 (guard_ring_r) — guard regiment ring
- 10236 精金指环 (adamant_ring) — mithril ring
- 10237 玄铁戒指 (xuantie_ring) — xuantie ring
- 10238 云母手镯 (mica_bracer) — mica bracer
- 10239 熔岩指环 (lava_ring) — Great Wasteland lava ring

---

## EPIC 史诗品级 (10250-10281) — 32 件

### 武器 weapon (4)
- 10250 大荒烈焰剑 (dahuang_flame_sword) — Great Wasteland lava refined flame sword, spirit energy veins glowing, red flame motifs
- 10251 青丘棅杖 (qingqiu_fae_staff) — Green Mound birch leaf staff, nature spirit energy, emerald glow
- 10252 机械重剑 (mech_greatsword) — mechanical craft greatsword, brass and steel mechanical parts
- 10253 精金长弓 (adamant_bow) — mithril long bow with golden rune channel

### 头部 head (4)
- 10254 机械头盔 (mech_helm_e) — mechanical craft helmet with HUD
- 10255 棅叶王冠 (birch_crown) — Green Mound birch leaf crown, emerald glow, nature runes
- 10256 大荒火冠 (dahuang_fire_crown) — Great Wasteland fire crown, lava glowing runes
- 10257 玄铁战冠 (xuantie_crown) — xuantie war crown, dark iron with glowing runes

### 身体 body (4)
- 10258 机械战甲 (mech_chest_e) — mechanical craft war armor
- 10259 精金战甲 (adamant_chest_e) — mithril forged war armor with iridescent sheen
- 10260 大荒熔岩甲 (dahuang_lava_chest) — Great Wasteland lava chest armor, magma veins
- 10261 棅叶裙 (birch_skirt) — Green Mound birch leaf skirt, emerald nature

### 腿部 legs (4)
- 10262 机械腿甲 (mech_legs_e) — mechanical craft leg armor
- 10263 精金腿甲 (adamant_legs_e) — mithril forged leg armor
- 10264 棅叶腿甲 (birch_legs) — Green Mound birch leaf leg armor
- 10265 大荒熔岩腿甲 (dahuang_lava_legs) — Great Wasteland lava leg armor

### 手部 hands (4)
- 10266 机械手套 (mech_gloves_e) — mechanical craft gloves
- 10267 精金护手 (adamant_gauntlets_e) — mithril forged gauntlets
- 10268 棅叶手套 (birch_gloves) — Green Mound birch leaf gloves
- 10269 玄铁重手套 (xuantie_heavy_gloves) — xuantie heavy gloves

### 足部 feet (4)
- 10270 机械战靴 (mech_boots_e) — mechanical craft war boots
- 10271 精金战靴 (adamant_boots_e) — mithril forged war boots
- 10272 棅叶靴 (birch_boots) — Green Mound birch leaf boots
- 10273 大荒熔岩靴 (dahuang_lava_boots) — Great Wasteland lava war boots

### 饰品1 accessory1 (4)
- 10274 机械核心 (mech_core_e) — mechanical core pendant
- 10275 棅玉坠 (birch_jade_pendant) — Green Mound birch jade pendant
- 10276 精金护符 (adamant_amulet) — mithril amulet
- 10277 玄铁徽章 (xuantie_badge) — xuantie badge

### 饰品2 accessory2 (4)
- 10278 机械环 (mech_ring_e) — mechanical craft ring
- 10279 精金戒 (adamant_ring_e) — mithril ring
- 10280 棅叶指环 (birch_ring) — Green Mound birch leaf ring
- 10281 大荒炎玉戒 (dahuang_fire_ring) — Great Wasteland flame jade ring

---

## LEGENDARY 传说品级 (10300-10323) — 24 件

### 武器 weapon (3)
- 10300 裁决圣剑 (juecai_holy_sword) — holy judgement holy sword, golden divine light, holy inscriptions
- 10301 混沌之刃 (chaos_blade_l) — legendary chaos blade, orange and purple chaotic energy
- 10302 神武巨剑 (shenwu_greatsword) — divine weapon greatsword, golden divine craftsmanship

### 头部 head (3)
- 10303 混沌王冠 (chaos_crown_l) — legendary chaos crown, 6 chaos gems
- 10304 裁决圣冠 (juecai_holy_crown) — holy judgement crown, golden holy light
- 10305 圣光头盔 (holy_light_helm) — holy light helmet, golden divine light

### 身体 body (3)
- 10306 混沌战甲 (chaos_chest_l) — legendary chaos war armor
- 10307 神武战甲 (shenwu_chest) — divine weapon war armor, golden divine craftsmanship
- 10308 裁决圣铠 (juecai_holy_armor) — holy judgement holy armor, golden inscriptions

### 腿部 legs (3)
- 10309 混沌腿甲 (chaos_legs_l) — legendary chaos leg armor
- 10310 神武腿甲 (shenwu_legs) — divine weapon leg armor
- 10311 裁决圣腿甲 (juecai_holy_legs) — holy judgement holy leg armor

### 手部 hands (3)
- 10312 裁决圣手甲 (juecai_holy_hands) — holy judgement holy hand armor
- 10313 混沌手套 (chaos_gloves_l) — legendary chaos gloves
- 10314 神武护手 (shenwu_gauntlets) — divine weapon gauntlets

### 足部 feet (3)
- 10315 混沌战靴 (chaos_boots_l) — legendary chaos war boots
- 10316 裁决圣靴 (juecai_holy_boots) — holy judgement holy boots
- 10317 神武长靴 (shenwu_long_boots) — divine weapon long boots

### 饰品1 accessory1 (3)
- 10318 混沌之眼 (chaos_eye_l) — legendary chaos eye amulet
- 10319 裁决圣物 (juecai_relic) — holy judgement relic, golden holy light
- 10320 神武护符 (shenwu_amulet) — divine weapon amulet

### 饰品2 accessory2 (3)
- 10321 混沌印记 (chaos_mark_l) — legendary chaos mark
- 10322 裁决圣戒 (juecai_holy_ring) — holy judgement holy ring
- 10323 神武手镯 (shenwu_bracer) — divine weapon bracer

---

## MYTHIC 神话品级 (10350-10365) — 16 件

### 武器 weapon (2)
- 10350 鸿蒙圣剑 (hongmeng_holy_sword) — primordial chaos holy sword, transparent crystal blade, purple and gold original energy, rainbow nebula aura
- 10351 太极神杖 (taiji_divine_staff) — taiji divine staff, black and white flowing yin-yang energy, rotating taiji diagram

### 头部 head (2)
- 10352 神农圣冠 (shennong_crown) — Shennong holy crown, emerald jade inlay, growing spirit grass on top
- 10353 伏羲神冠 (fuxi_crown) — Fuxi divine crown, silver metal, rotating bagua diagram

### 身体 body (2)
- 10354 盘古神甲 (pangu_armor) — Pangu divine armor, primordial crystal stone, creation axe imprint on chest
- 10355 女娲神袍 (nuwa_robe) — Nüwa divine robe, seven-color brocade, five-color stone on shoulders

### 腿部 legs (2)
- 10356 玄黄神腿 (xuanhuang_legs) — Xuanhuang divine leg armor, black-yellow flowing energy
- 10357 鸿蒙神腿 (hongmeng_legs) — primordial divine leg armor, purple energy blooms under feet

### 手部 hands (2)
- 10358 神农圣手 (shennong_hands) — Shennong holy hand, emerald jade with hundred herbs diagram on palm
- 10359 伏羲神手 (fuxi_hands) — Fuxi divine hand, silver metal with bagua diagram on back

### 足部 feet (2)
- 10360 玄黄神靴 (xuanhuang_boots) — Xuanhuang divine boot, black-yellow flowing
- 10361 盘古神靴 (pangu_boots) — Pangu divine boot, primordial crystal stone

### 饰品1 accessory1 (2)
- 10362 太极神坠 (taiji_pendant) — taiji divine pendant, rotating taiji diagram
- 10363 女娲圣物 (nuwa_relic) — Nüwa holy relic, five-color stone pendant

### 饰品2 accessory2 (2)
- 10364 太极神戒 (taiji_ring) — taiji divine ring, black-white yin-yang flowing
- 10365 伏羲神戒 (fuxi_ring) — Fuxi divine ring, silver metal with bagua diagram

---

## 总计
- LEGACY: 41 件 (6+5+5+5+5+5+5+5)
- COMMON: 48 件 (6+6+6+6+6+6+6+6)
- UNCOMMON: 48 件 (6+6+6+6+6+6+6+6)
- RARE: 40 件 (5+5+5+5+5+5+5+5)
- EPIC: 32 件 (4+4+4+4+4+4+4+4)
- LEGENDARY: 24 件 (3+3+3+3+3+3+3+3)
- MYTHIC: 16 件 (2+2+2+2+2+2+2+2)
- **总计 249 件**
