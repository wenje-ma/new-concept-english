# 国际音标（IPA）Unicode 速查表

> 用途：查 IPA 符号对应的 Unicode 码位，直接复制粘贴。
> 符号集以 Kiel 官方音标表（IPA Chart, 2020）为准；码位与名称取自 Unicode 字符数据库（`unicodedata`）。

**怎么用**

- 想复制某个音素：直接选中表格「字符」列里的那个字符。
- 想知道某个字符是什么：把码位 `U+XXXX` 拿去搜索，或看「Unicode 名称」列。
- 变音符号（第六节）是组合字符，必须贴在音素后面才会显示，单独一个看不出效果；表里用虚线圆圈 `◌` 占位。
- 复制到 Word / 网页里显示不出来时，换用 Charis SIL、Doulos SIL 或 Noto Sans IPA 这类带完整 IPA 的字体。

---

## 0. 一键复制（按组排列）

整段选中复制即可；每组一行，行内符号用空格分隔，没有任何注释字符干扰。

```text
p b t d ʈ ɖ c ɟ k ɡ q ɢ ʔ
m ɱ n ɳ ɲ ŋ ɴ
ʙ r ʀ
ⱱ ɾ ɽ
ɸ β f v θ ð s z ʃ ʒ ʂ ʐ ç ʝ x ɣ χ ʁ ħ ʕ h ɦ
ɬ ɮ
ʋ ɹ ɻ j ɰ
l ɭ ʎ ʟ

ʘ ǀ ǃ ǂ ǁ
ɓ ɗ ʄ ɠ ʛ
ʼ

ʍ w ɥ ɕ ʑ ɺ ɧ ʜ ʢ ʡ

i y ɨ ʉ ɯ u
ɪ ʏ ʊ
e ø ɘ ɵ ɤ o
ə
ɛ œ ɜ ɞ ʌ ɔ
æ ɐ
a ɶ ɑ ɒ
ɚ ɝ

ˈ ˌ ː ˑ | ‖ ‿ .

˥ ˦ ˧ ˨ ˩ ↓ ↑ ↗ ↘
```

---

## 1. 肺部气流辅音 Pulmonic Consonants

每个音素按「清／浊」成对收录，说明列里标明清浊和发音部位。

### 塞音 Plosive

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `p` | U+0070 | LATIN SMALL LETTER P | 双唇清塞音 |
| `b` | U+0062 | LATIN SMALL LETTER B | 双唇浊塞音 |
| `t` | U+0074 | LATIN SMALL LETTER T | 齿龈清塞音 |
| `d` | U+0064 | LATIN SMALL LETTER D | 齿龈浊塞音 |
| `ʈ` | U+0288 | LATIN SMALL LETTER T WITH RETROFLEX HOOK | 卷舌清塞音 |
| `ɖ` | U+0256 | LATIN SMALL LETTER D WITH TAIL | 卷舌浊塞音 |
| `c` | U+0063 | LATIN SMALL LETTER C | 硬腭清塞音 |
| `ɟ` | U+025F | LATIN SMALL LETTER DOTLESS J WITH STROKE | 硬腭浊塞音 |
| `k` | U+006B | LATIN SMALL LETTER K | 软腭清塞音 |
| `ɡ` | U+0261 | LATIN SMALL LETTER SCRIPT G | 软腭浊塞音 |
| `q` | U+0071 | LATIN SMALL LETTER Q | 小舌清塞音 |
| `ɢ` | U+0262 | LATIN LETTER SMALL CAPITAL G | 小舌浊塞音 |
| `ʔ` | U+0294 | LATIN LETTER GLOTTAL STOP | 声门塞音 |

### 鼻音 Nasal

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `m` | U+006D | LATIN SMALL LETTER M | 双唇鼻音 |
| `ɱ` | U+0271 | LATIN SMALL LETTER M WITH HOOK | 唇齿鼻音 |
| `n` | U+006E | LATIN SMALL LETTER N | 齿龈鼻音 |
| `ɳ` | U+0273 | LATIN SMALL LETTER N WITH RETROFLEX HOOK | 卷舌鼻音 |
| `ɲ` | U+0272 | LATIN SMALL LETTER N WITH LEFT HOOK | 硬腭鼻音 |
| `ŋ` | U+014B | LATIN SMALL LETTER ENG | 软腭鼻音 |
| `ɴ` | U+0274 | LATIN LETTER SMALL CAPITAL N | 小舌鼻音 |

### 颤音 Trill

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ʙ` | U+0299 | LATIN LETTER SMALL CAPITAL B | 双唇颤音 |
| `r` | U+0072 | LATIN SMALL LETTER R | 齿龈颤音 |
| `ʀ` | U+0280 | LATIN LETTER SMALL CAPITAL R | 小舌颤音 |

### 闪音／搭音 Tap or Flap

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ⱱ` | U+2C71 | LATIN SMALL LETTER V WITH RIGHT HOOK | 唇齿闪音 |
| `ɾ` | U+027E | LATIN SMALL LETTER R WITH FISHHOOK | 齿龈闪音 |
| `ɽ` | U+027D | LATIN SMALL LETTER R WITH TAIL | 卷舌闪音 |

### 擦音 Fricative

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ɸ` | U+0278 | LATIN SMALL LETTER PHI | 双唇清擦音 |
| `β` | U+03B2 | GREEK SMALL LETTER BETA | 双唇浊擦音 |
| `f` | U+0066 | LATIN SMALL LETTER F | 唇齿清擦音 |
| `v` | U+0076 | LATIN SMALL LETTER V | 唇齿浊擦音 |
| `θ` | U+03B8 | GREEK SMALL LETTER THETA | 齿清擦音 |
| `ð` | U+00F0 | LATIN SMALL LETTER ETH | 齿浊擦音 |
| `s` | U+0073 | LATIN SMALL LETTER S | 齿龈清擦音 |
| `z` | U+007A | LATIN SMALL LETTER Z | 齿龈浊擦音 |
| `ʃ` | U+0283 | LATIN SMALL LETTER ESH | 龈后清擦音 |
| `ʒ` | U+0292 | LATIN SMALL LETTER EZH | 龈后浊擦音 |
| `ʂ` | U+0282 | LATIN SMALL LETTER S WITH HOOK | 卷舌清擦音 |
| `ʐ` | U+0290 | LATIN SMALL LETTER Z WITH RETROFLEX HOOK | 卷舌浊擦音 |
| `ç` | U+00E7 | LATIN SMALL LETTER C WITH CEDILLA | 硬腭清擦音 |
| `ʝ` | U+029D | LATIN SMALL LETTER J WITH CROSSED-TAIL | 硬腭浊擦音 |
| `x` | U+0078 | LATIN SMALL LETTER X | 软腭清擦音 |
| `ɣ` | U+0263 | LATIN SMALL LETTER GAMMA | 软腭浊擦音 |
| `χ` | U+03C7 | GREEK SMALL LETTER CHI | 小舌清擦音 |
| `ʁ` | U+0281 | LATIN LETTER SMALL CAPITAL INVERTED R | 小舌浊擦音 |
| `ħ` | U+0127 | LATIN SMALL LETTER H WITH STROKE | 咽清擦音 |
| `ʕ` | U+0295 | LATIN LETTER PHARYNGEAL VOICED FRICATIVE | 咽浊擦音 |
| `h` | U+0068 | LATIN SMALL LETTER H | 声门清擦音 |
| `ɦ` | U+0266 | LATIN SMALL LETTER H WITH HOOK | 声门浊擦音 |

### 边擦音 Lateral fricative

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ɬ` | U+026C | LATIN SMALL LETTER L WITH BELT | 齿龈清边擦音 |
| `ɮ` | U+026E | LATIN SMALL LETTER LEZH | 齿龈浊边擦音 |

### 近音 Approximant

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ʋ` | U+028B | LATIN SMALL LETTER V WITH HOOK | 唇齿近音 |
| `ɹ` | U+0279 | LATIN SMALL LETTER TURNED R | 齿龈近音 |
| `ɻ` | U+027B | LATIN SMALL LETTER TURNED R WITH HOOK | 卷舌近音 |
| `j` | U+006A | LATIN SMALL LETTER J | 硬腭近音 |
| `ɰ` | U+0270 | LATIN SMALL LETTER TURNED M WITH LONG LEG | 软腭近音 |

### 边近音 Lateral approximant

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `l` | U+006C | LATIN SMALL LETTER L | 齿龈边近音 |
| `ɭ` | U+026D | LATIN SMALL LETTER L WITH RETROFLEX HOOK | 卷舌边近音 |
| `ʎ` | U+028E | LATIN SMALL LETTER TURNED Y | 硬腭边近音 |
| `ʟ` | U+029F | LATIN LETTER SMALL CAPITAL L | 软腭边近音 |

## 2. 非肺部气流辅音 Non-pulmonic Consonants

### 吸气音 Clicks

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ʘ` | U+0298 | LATIN LETTER BILABIAL CLICK | 双唇吸气音 |
| `ǀ` | U+01C0 | LATIN LETTER DENTAL CLICK | 齿吸气音 |
| `ǃ` | U+01C3 | LATIN LETTER RETROFLEX CLICK | 龈后吸气音 |
| `ǂ` | U+01C2 | LATIN LETTER ALVEOLAR CLICK | 龈腭吸气音 |
| `ǁ` | U+01C1 | LATIN LETTER LATERAL CLICK | 齿龈边吸气音 |

### 浊内爆音 Voiced implosives

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ɓ` | U+0253 | LATIN SMALL LETTER B WITH HOOK | 双唇内爆音 |
| `ɗ` | U+0257 | LATIN SMALL LETTER D WITH HOOK | 齿龈内爆音 |
| `ʄ` | U+0284 | LATIN SMALL LETTER DOTLESS J WITH STROKE AND HOOK | 硬腭内爆音 |
| `ɠ` | U+0260 | LATIN SMALL LETTER G WITH HOOK | 软腭内爆音 |
| `ʛ` | U+029B | LATIN LETTER SMALL CAPITAL G WITH HOOK | 小舌内爆音 |

### 挤喉音标记 Ejectives

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ʼ` | U+02BC | MODIFIER LETTER APOSTROPHE | 挤喉音附加符号（写在音素后，如 pʼ） |

## 3. 其他符号 Other Symbols

Kiel 表把下面这些单独列出，它们不进入上面的部位／方式方格。

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ʍ` | U+028D | LATIN SMALL LETTER TURNED W | 清唇软腭擦音（如英语 which） |
| `w` | U+0077 | LATIN SMALL LETTER W | 浊唇软腭近音（普通字母 w，U+0077） |
| `ɥ` | U+0265 | LATIN SMALL LETTER TURNED H | 浊唇硬腭近音（法语 lui） |
| `ɕ` | U+0255 | LATIN SMALL LETTER C WITH CURL | 龈腭清擦音（日语、汉语拼音 x） |
| `ʑ` | U+0291 | LATIN SMALL LETTER Z WITH CURL | 龈腭浊擦音（日语、汉语拼音 j） |
| `ɺ` | U+027A | LATIN SMALL LETTER TURNED R WITH LONG LEG | 齿龈边闪音（日语 ら 行） |
| `ɧ` | U+0267 | LATIN SMALL LETTER HENG WITH HOOK | 清龈腭擦音（瑞典语 sje） |
| `ʜ` | U+029C | LATIN LETTER SMALL CAPITAL H | 清会厌擦音 |
| `ʢ` | U+02A2 | LATIN LETTER REVERSED GLOTTAL STOP WITH STROKE | 浊会厌擦音 |
| `ʡ` | U+02A1 | LATIN LETTER GLOTTAL STOP WITH STROKE | 会厌塞音 |

## 4. 元音 Vowels

成对时右侧为圆唇元音。

### 闭 Close

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `i` | U+0069 | LATIN SMALL LETTER I | 前、不圆唇 |
| `y` | U+0079 | LATIN SMALL LETTER Y | 前、圆唇 |
| `ɨ` | U+0268 | LATIN SMALL LETTER I WITH STROKE | 央、不圆唇 |
| `ʉ` | U+0289 | LATIN SMALL LETTER U BAR | 央、圆唇 |
| `ɯ` | U+026F | LATIN SMALL LETTER TURNED M | 后、不圆唇 |
| `u` | U+0075 | LATIN SMALL LETTER U | 后、圆唇 |

### 次闭 Near-close

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ɪ` | U+026A | LATIN LETTER SMALL CAPITAL I | 前、不圆唇 |
| `ʏ` | U+028F | LATIN LETTER SMALL CAPITAL Y | 前、圆唇 |
| `ʊ` | U+028A | LATIN SMALL LETTER UPSILON | 后、圆唇 |

### 半闭 Close-mid

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `e` | U+0065 | LATIN SMALL LETTER E | 前、不圆唇 |
| `ø` | U+00F8 | LATIN SMALL LETTER O WITH STROKE | 前、圆唇 |
| `ɘ` | U+0258 | LATIN SMALL LETTER REVERSED E | 央、不圆唇 |
| `ɵ` | U+0275 | LATIN SMALL LETTER BARRED O | 央、圆唇 |
| `ɤ` | U+0264 | LATIN SMALL LETTER RAMS HORN | 后、不圆唇 |
| `o` | U+006F | LATIN SMALL LETTER O | 后、圆唇 |

### 中央 Mid

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ə` | U+0259 | LATIN SMALL LETTER SCHWA | 中央元音 schwa |

### 半开 Open-mid

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ɛ` | U+025B | LATIN SMALL LETTER OPEN E | 前、不圆唇 |
| `œ` | U+0153 | LATIN SMALL LIGATURE OE | 前、圆唇 |
| `ɜ` | U+025C | LATIN SMALL LETTER REVERSED OPEN E | 央、不圆唇 |
| `ɞ` | U+025E | LATIN SMALL LETTER CLOSED REVERSED OPEN E | 央、圆唇 |
| `ʌ` | U+028C | LATIN SMALL LETTER TURNED V | 后、不圆唇 |
| `ɔ` | U+0254 | LATIN SMALL LETTER OPEN O | 后、圆唇 |

### 次开 Near-open

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `æ` | U+00E6 | LATIN SMALL LETTER AE | 前、不圆唇 |
| `ɐ` | U+0250 | LATIN SMALL LETTER TURNED A | 央、不圆唇 |

### 开 Open

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `a` | U+0061 | LATIN SMALL LETTER A | 前、不圆唇 |
| `ɶ` | U+0276 | LATIN LETTER SMALL CAPITAL OE | 前、圆唇 |
| `ɑ` | U+0251 | LATIN SMALL LETTER ALPHA | 后、不圆唇 |
| `ɒ` | U+0252 | LATIN SMALL LETTER TURNED ALPHA | 后、圆唇 |

### 补充：美式英语常用卷舌元音（不在 Kiel 表内）

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ɚ` | U+025A | LATIN SMALL LETTER SCHWA WITH HOOK | 卷舌 schwa（美式英语 /ɚ/，非 Kiel 表） |
| `ɝ` | U+025D | LATIN SMALL LETTER REVERSED OPEN E WITH HOOK | 重读卷舌元音（美式英语 /ɝ/，非 Kiel 表） |

## 5. 超音段符号 Suprasegmentals

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `ˈ` | U+02C8 | MODIFIER LETTER VERTICAL LINE | 主重音（primary stress） |
| `ˌ` | U+02CC | MODIFIER LETTER LOW VERTICAL LINE | 次重音（secondary stress） |
| `ː` | U+02D0 | MODIFIER LETTER TRIANGULAR COLON | 长音（long） |
| `ˑ` | U+02D1 | MODIFIER LETTER HALF TRIANGULAR COLON | 半长音（half-long） |
| `̆` | U+0306 | COMBINING BREVE | 超短（extra-short，组合符号，写在音素上方） |
| &#124; | U+007C | VERTICAL LINE | 小（音步）界线（minor foot group；普通竖线 U+007C，下表格内用 HTML 实体显示以免破坏表格） |
| `‖` | U+2016 | DOUBLE VERTICAL LINE | 大（语调）界线（major intonation group） |
| `‿` | U+203F | UNDERTIE | 连读符号（linking，无停顿） |
| `.` | U+002E | FULL STOP | 音节分隔（syllable break，普通句点 U+002E） |

## 6. 变音符号 Diacritics（组合附加符号）

表里大多数是 *组合字符*（Unicode 类别 Mn），本身不占位，要写在基础音素后面；上标字母类（`ʰ ⁿ ˡ ˠ ˤ ʲ ʷ ˞`）是独立的修饰字符，同样跟在音素后面。
示例：`n̥` 清化 n、`ẽ` 鼻化 e、`tʰ` 送气 t。

| 字符 | Unicode | Unicode 名称 | 说明 |
|---|---|---|---|
| `◌̥` | U+0325 | COMBINING RING BELOW | 清化（voiceless） |
| `◌̬` | U+032C | COMBINING CARON BELOW | 浊化（voiced） |
| `◌ʰ` | U+02B0 | MODIFIER LETTER SMALL H | 送气（aspirated，上标 h） |
| `◌̤` | U+0324 | COMBINING DIAERESIS BELOW | 气声／浊送气（breathy voiced） |
| `◌̰` | U+0330 | COMBINING TILDE BELOW | 嘎裂声（creaky voiced） |
| `◌̼` | U+033C | COMBINING SEAGULL BELOW | 舌唇化（linguolabial） |
| `◌̪` | U+032A | COMBINING BRIDGE BELOW | 齿化（dental） |
| `◌̺` | U+033A | COMBINING INVERTED BRIDGE BELOW | 舌尖化（apical） |
| `◌̻` | U+033B | COMBINING SQUARE BELOW | 舌叶化（laminal） |
| `◌̃` | U+0303 | COMBINING TILDE | 鼻化（nasalized） |
| `◌ⁿ` | U+207F | SUPERSCRIPT LATIN SMALL LETTER N | 鼻除阻（nasal release，上标 n） |
| `◌ˡ` | U+02E1 | MODIFIER LETTER SMALL L | 边除阻（lateral release，上标 l） |
| `◌̚` | U+031A | COMBINING LEFT ANGLE ABOVE | 不爆破／无声除阻（no audible release） |
| `◌̴` | U+0334 | COMBINING TILDE OVERLAY | 软腭化或咽化（velarized / pharyngealized） |
| `◌̝` | U+031D | COMBINING UP TACK BELOW | 抬高（raised） |
| `◌̞` | U+031E | COMBINING DOWN TACK BELOW | 降低（lowered） |
| `◌̘` | U+0318 | COMBINING LEFT TACK BELOW | 舌根前移（advanced tongue root） |
| `◌̙` | U+0319 | COMBINING RIGHT TACK BELOW | 舌根后缩（retracted tongue root） |
| `◌̈` | U+0308 | COMBINING DIAERESIS | 央化（centralized） |
| `◌̽` | U+033D | COMBINING X ABOVE | 半央化（mid-centralized） |
| `◌̩` | U+0329 | COMBINING VERTICAL LINE BELOW | 成音节（syllabic） |
| `◌̯` | U+032F | COMBINING INVERTED BREVE BELOW | 非音节（non-syllabic） |
| `◌˞` | U+02DE | MODIFIER LETTER RHOTIC HOOK | 卷舌／儿化（rhoticity，上标小 r 钩） |
| `◌ˠ` | U+02E0 | MODIFIER LETTER SMALL GAMMA | 软腭化（velarized，上标 ˠ） |
| `◌ˤ` | U+02E4 | MODIFIER LETTER SMALL REVERSED GLOTTAL STOP | 咽化（pharyngealized，上标 ˤ） |
| `◌ʲ` | U+02B2 | MODIFIER LETTER SMALL J | 腭化（palatalized，上标 j） |
| `◌ʷ` | U+02B7 | MODIFIER LETTER SMALL W | 唇化（labialized，上标 w） |
| `◌͜` | U+035C | COMBINING DOUBLE BREVE BELOW | 连音符·下方（tie bar below，如 a͜e） |
| `◌͡` | U+0361 | COMBINING DOUBLE INVERTED BREVE | 连音符·上方（tie bar above，如 t͡ʒ） |

纯符号写法（不含占位的 `◌`）：这一行里的符号可以直接跟在音素后面使用，排序与上表一致。

```text
̥ ̬ ʰ ̤ ̰ ̼ ̪ ̺ ̻ ̃ ⁿ ˡ ̚ ̴ ̝ ̞ ̘ ̙ ̈ ̽ ̩ ̯ ˞ ˠ ˤ ʲ ʷ ͜ ͡
```

## 7. 声调与词调 Tones and Word Accents

| 字符 | Unicode | Unicode 名称 | 含义 |
|---|---|---|---|
| `˥` | U+02E5 | MODIFIER LETTER EXTRA-HIGH TONE BAR | 最高（extra-high，tone 5） |
| `˦` | U+02E6 | MODIFIER LETTER HIGH TONE BAR | 次高（high，tone 4） |
| `˧` | U+02E7 | MODIFIER LETTER MID TONE BAR | 中（mid，tone 3） |
| `˨` | U+02E8 | MODIFIER LETTER LOW TONE BAR | 次低（low，tone 2） |
| `˩` | U+02E9 | MODIFIER LETTER EXTRA-LOW TONE BAR | 最低（extra-low，tone 1） |
| `↓` | U+2193 | DOWNWARDS ARROW | 降阶（downstep ↓） |
| `↑` | U+2191 | UPWARDS ARROW | 升阶（upstep ↑） |
| `↗` | U+2197 | NORTH EAST ARROW | 全局上升（global rise ↗） |
| `↘` | U+2198 | SOUTH EAST ARROW | 全局下降（global fall ↘） |

### 声调组合（五度标记法）

单个音高档位 `˥ ˦ ˧ ˨ ˩` 直接连写就是调型。例如普通话四声（阴平 55、阳平 35、上声 214、去声 51）写作 `˥˥ ˧˥ ˨˩˦ ˥˩`。

| 字符 | Unicode（两字符序列） | Unicode 名称 | 含义 |
|---|---|---|---|
| `˥˩` | U+02E5 + U+02E9 | MODIFIER LETTER EXTRA-HIGH TONE BAR + MODIFIER LETTER EXTRA-LOW TONE BAR | 全降 5→1 |
| `˩˥` | U+02E9 + U+02E5 | MODIFIER LETTER EXTRA-LOW TONE BAR + MODIFIER LETTER EXTRA-HIGH TONE BAR | 全升 1→5 |
| `˧˥` | U+02E7 + U+02E5 | MODIFIER LETTER MID TONE BAR + MODIFIER LETTER EXTRA-HIGH TONE BAR | 中升 3→5 |
| `˥˧` | U+02E5 + U+02E7 | MODIFIER LETTER EXTRA-HIGH TONE BAR + MODIFIER LETTER MID TONE BAR | 高降 5→3 |
| `˨˦` | U+02E8 + U+02E6 | MODIFIER LETTER LOW TONE BAR + MODIFIER LETTER HIGH TONE BAR | 低升 2→4 |
| `˦˨` | U+02E6 + U+02E8 | MODIFIER LETTER HIGH TONE BAR + MODIFIER LETTER LOW TONE BAR | 高降 4→2 |
| `˥˥` | U+02E5 + U+02E5 | MODIFIER LETTER EXTRA-HIGH TONE BAR + MODIFIER LETTER EXTRA-HIGH TONE BAR | 高平 5→5 |
| `˩˩` | U+02E9 + U+02E9 | MODIFIER LETTER EXTRA-LOW TONE BAR + MODIFIER LETTER EXTRA-LOW TONE BAR | 低平 1→1 |

## 8. 附：IPA Extensions 区块全集（U+0250–U+02AF）

上面各表只收录 Kiel 表出现的符号。Unicode 的 IPA Extensions 区块另外还留了很多位置给别的语言用，
整块列在这里，方便你确认「某个看起来像 IPA 的字符」到底是哪一个码位。

| 字符 | Unicode | Unicode 名称 |
|---|---|---|
| `ɐ` | U+0250 | LATIN SMALL LETTER TURNED A |
| `ɑ` | U+0251 | LATIN SMALL LETTER ALPHA |
| `ɒ` | U+0252 | LATIN SMALL LETTER TURNED ALPHA |
| `ɓ` | U+0253 | LATIN SMALL LETTER B WITH HOOK |
| `ɔ` | U+0254 | LATIN SMALL LETTER OPEN O |
| `ɕ` | U+0255 | LATIN SMALL LETTER C WITH CURL |
| `ɖ` | U+0256 | LATIN SMALL LETTER D WITH TAIL |
| `ɗ` | U+0257 | LATIN SMALL LETTER D WITH HOOK |
| `ɘ` | U+0258 | LATIN SMALL LETTER REVERSED E |
| `ə` | U+0259 | LATIN SMALL LETTER SCHWA |
| `ɚ` | U+025A | LATIN SMALL LETTER SCHWA WITH HOOK |
| `ɛ` | U+025B | LATIN SMALL LETTER OPEN E |
| `ɜ` | U+025C | LATIN SMALL LETTER REVERSED OPEN E |
| `ɝ` | U+025D | LATIN SMALL LETTER REVERSED OPEN E WITH HOOK |
| `ɞ` | U+025E | LATIN SMALL LETTER CLOSED REVERSED OPEN E |
| `ɟ` | U+025F | LATIN SMALL LETTER DOTLESS J WITH STROKE |
| `ɠ` | U+0260 | LATIN SMALL LETTER G WITH HOOK |
| `ɡ` | U+0261 | LATIN SMALL LETTER SCRIPT G |
| `ɢ` | U+0262 | LATIN LETTER SMALL CAPITAL G |
| `ɣ` | U+0263 | LATIN SMALL LETTER GAMMA |
| `ɤ` | U+0264 | LATIN SMALL LETTER RAMS HORN |
| `ɥ` | U+0265 | LATIN SMALL LETTER TURNED H |
| `ɦ` | U+0266 | LATIN SMALL LETTER H WITH HOOK |
| `ɧ` | U+0267 | LATIN SMALL LETTER HENG WITH HOOK |
| `ɨ` | U+0268 | LATIN SMALL LETTER I WITH STROKE |
| `ɩ` | U+0269 | LATIN SMALL LETTER IOTA |
| `ɪ` | U+026A | LATIN LETTER SMALL CAPITAL I |
| `ɫ` | U+026B | LATIN SMALL LETTER L WITH MIDDLE TILDE |
| `ɬ` | U+026C | LATIN SMALL LETTER L WITH BELT |
| `ɭ` | U+026D | LATIN SMALL LETTER L WITH RETROFLEX HOOK |
| `ɮ` | U+026E | LATIN SMALL LETTER LEZH |
| `ɯ` | U+026F | LATIN SMALL LETTER TURNED M |
| `ɰ` | U+0270 | LATIN SMALL LETTER TURNED M WITH LONG LEG |
| `ɱ` | U+0271 | LATIN SMALL LETTER M WITH HOOK |
| `ɲ` | U+0272 | LATIN SMALL LETTER N WITH LEFT HOOK |
| `ɳ` | U+0273 | LATIN SMALL LETTER N WITH RETROFLEX HOOK |
| `ɴ` | U+0274 | LATIN LETTER SMALL CAPITAL N |
| `ɵ` | U+0275 | LATIN SMALL LETTER BARRED O |
| `ɶ` | U+0276 | LATIN LETTER SMALL CAPITAL OE |
| `ɷ` | U+0277 | LATIN SMALL LETTER CLOSED OMEGA |
| `ɸ` | U+0278 | LATIN SMALL LETTER PHI |
| `ɹ` | U+0279 | LATIN SMALL LETTER TURNED R |
| `ɺ` | U+027A | LATIN SMALL LETTER TURNED R WITH LONG LEG |
| `ɻ` | U+027B | LATIN SMALL LETTER TURNED R WITH HOOK |
| `ɼ` | U+027C | LATIN SMALL LETTER R WITH LONG LEG |
| `ɽ` | U+027D | LATIN SMALL LETTER R WITH TAIL |
| `ɾ` | U+027E | LATIN SMALL LETTER R WITH FISHHOOK |
| `ɿ` | U+027F | LATIN SMALL LETTER REVERSED R WITH FISHHOOK |
| `ʀ` | U+0280 | LATIN LETTER SMALL CAPITAL R |
| `ʁ` | U+0281 | LATIN LETTER SMALL CAPITAL INVERTED R |
| `ʂ` | U+0282 | LATIN SMALL LETTER S WITH HOOK |
| `ʃ` | U+0283 | LATIN SMALL LETTER ESH |
| `ʄ` | U+0284 | LATIN SMALL LETTER DOTLESS J WITH STROKE AND HOOK |
| `ʅ` | U+0285 | LATIN SMALL LETTER SQUAT REVERSED ESH |
| `ʆ` | U+0286 | LATIN SMALL LETTER ESH WITH CURL |
| `ʇ` | U+0287 | LATIN SMALL LETTER TURNED T |
| `ʈ` | U+0288 | LATIN SMALL LETTER T WITH RETROFLEX HOOK |
| `ʉ` | U+0289 | LATIN SMALL LETTER U BAR |
| `ʊ` | U+028A | LATIN SMALL LETTER UPSILON |
| `ʋ` | U+028B | LATIN SMALL LETTER V WITH HOOK |
| `ʌ` | U+028C | LATIN SMALL LETTER TURNED V |
| `ʍ` | U+028D | LATIN SMALL LETTER TURNED W |
| `ʎ` | U+028E | LATIN SMALL LETTER TURNED Y |
| `ʏ` | U+028F | LATIN LETTER SMALL CAPITAL Y |
| `ʐ` | U+0290 | LATIN SMALL LETTER Z WITH RETROFLEX HOOK |
| `ʑ` | U+0291 | LATIN SMALL LETTER Z WITH CURL |
| `ʒ` | U+0292 | LATIN SMALL LETTER EZH |
| `ʓ` | U+0293 | LATIN SMALL LETTER EZH WITH CURL |
| `ʔ` | U+0294 | LATIN LETTER GLOTTAL STOP |
| `ʕ` | U+0295 | LATIN LETTER PHARYNGEAL VOICED FRICATIVE |
| `ʖ` | U+0296 | LATIN LETTER INVERTED GLOTTAL STOP |
| `ʗ` | U+0297 | LATIN LETTER STRETCHED C |
| `ʘ` | U+0298 | LATIN LETTER BILABIAL CLICK |
| `ʙ` | U+0299 | LATIN LETTER SMALL CAPITAL B |
| `ʚ` | U+029A | LATIN SMALL LETTER CLOSED OPEN E |
| `ʛ` | U+029B | LATIN LETTER SMALL CAPITAL G WITH HOOK |
| `ʜ` | U+029C | LATIN LETTER SMALL CAPITAL H |
| `ʝ` | U+029D | LATIN SMALL LETTER J WITH CROSSED-TAIL |
| `ʞ` | U+029E | LATIN SMALL LETTER TURNED K |
| `ʟ` | U+029F | LATIN LETTER SMALL CAPITAL L |
| `ʠ` | U+02A0 | LATIN SMALL LETTER Q WITH HOOK |
| `ʡ` | U+02A1 | LATIN LETTER GLOTTAL STOP WITH STROKE |
| `ʢ` | U+02A2 | LATIN LETTER REVERSED GLOTTAL STOP WITH STROKE |
| `ʣ` | U+02A3 | LATIN SMALL LETTER DZ DIGRAPH |
| `ʤ` | U+02A4 | LATIN SMALL LETTER DEZH DIGRAPH |
| `ʥ` | U+02A5 | LATIN SMALL LETTER DZ DIGRAPH WITH CURL |
| `ʦ` | U+02A6 | LATIN SMALL LETTER TS DIGRAPH |
| `ʧ` | U+02A7 | LATIN SMALL LETTER TESH DIGRAPH |
| `ʨ` | U+02A8 | LATIN SMALL LETTER TC DIGRAPH WITH CURL |
| `ʩ` | U+02A9 | LATIN SMALL LETTER FENG DIGRAPH |
| `ʪ` | U+02AA | LATIN SMALL LETTER LS DIGRAPH |
| `ʫ` | U+02AB | LATIN SMALL LETTER LZ DIGRAPH |
| `ʬ` | U+02AC | LATIN LETTER BILABIAL PERCUSSIVE |
| `ʭ` | U+02AD | LATIN LETTER BIDENTAL PERCUSSIVE |
| `ʮ` | U+02AE | LATIN SMALL LETTER TURNED H WITH FISHHOOK |
| `ʯ` | U+02AF | LATIN SMALL LETTER TURNED H WITH FISHHOOK AND TAIL |

## 9. 常见陷阱：看起来一样，码位不同

搜索或输入音标时最常见的坑：字形一样、码位不同，复制过去字体就崩。

| 音标字符 | 别写成 | 说明 |
|---|---|---|
| `ɡ`（U+0261） | `g` | 软腭浊塞音必须用 U+0261；ASCII g 是 U+0067，多数音标字体里字形不同 |
| `ː`（U+02D0） | `:` | 长音符号不是冒号；冒号不会拉长元音 |
| `ˈ`（U+02C8） | `'` | 重音符号不是撇号 |
| `ʼ`（U+02BC） | `'` | 挤喉音符号不是撇号 |
| `ʃ`（U+0283） | `sh` | 英语 sh 的音标是一个字符 ʃ，不是 s+h |
| `ʒ`（U+0292） | `zh` | 法语 j／英语 measure 的音标是一个字符 ʒ |
| `θ`（U+03B8） | `th` | think 的音标是 θ（希腊字母 theta） |
| `ð`（U+00F0） | `th` | this 的音标是 ð（eth） |
| `ŋ`（U+014B） | `ng` | sing 的音标结尾是 ŋ |
| `ɑ`（U+0251） | `a` | 英式 car /ɑː/ 用 ɑ，与 a 不同 |
| `ə`（U+0259） | `e` | 弱读元音用 ə（schwa），不是 e |
| `ɜ`（U+025C） | `3 / ε` | 英式 bird /ɜː/ 用 ɜ |

---

共收录 157 条符号（同一条目在不同类别里重复出现时各算一条；第 8 节整区块另计）。码位由字符本身计算，名称用 `unicodedata.name()` 反查核对。
