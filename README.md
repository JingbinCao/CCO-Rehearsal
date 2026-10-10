# CCO-Rehearsal · 排练节拍器

**在线使用 / Open it:** https://jingbincao.github.io/CCO-Rehearsal/

中文 | [English](#english)

为《大潮》和《七彩之和》第五乐章《赤·火之歌》排练做的节拍器网页。它按每个小节的拍号和分组打八分音符，不用自己数复合拍子。

## 怎么用

1. 选曲目：大潮，或七彩之和。
2. 输入起始小节，速度会自动填成谱面速度。
3. 想换速度，可以用 −/+、滑杆，或者直接输入数字。
4. 点"开始"，或者按空格键。

## 声音和显示

- **小节第一拍**：最高、最响的音。
- **每组第一个八分**：重音，画面上显示为八分音符。
- **组里其余的八分**：轻的分拍，画面上显示为八分休止符。
- 画面上同时显示 4 个小节：前 1 个、当前、后 2 个。每响一声，对应的音符会亮起来。

## 分组

- **传统拍号**：按两个八分一组。4/4 = 2+2+2+2，3/4 = 2+2+2，2/4 = 2+2，6/4 = 2+2+2+2+2+2。
- **八分拍号**：按谱上的分组。10/8 = 3+3+2+2，7/8 = 3+2+2，5/8 = 3+2，6/8 = 3+3，8/8 = 2+2+2+2。

## 其他功能

- **跟随谱面变速**：进入新的速度段时，按你当前设的百分比自动换算速度。
- **渐快 / 渐慢**：rit. 和 accel. 处可以开启逐拍均匀变速，目标速度可以改。
- **结束小节和循环**：用来反复练一段。
- **拍号表和速度表**：点击其中任意一行，就从那里开始。

## 曲目

| 曲目 | 范围 | 速度 |
|---|---|---|
| 大潮（王云飞 曲） | 1–286 小节 | ♩=96 → 33 小节 ♩=152 → 123 小节 ♩=66 rubato → 175 小节 ♩=160 |
| 七彩之和 · 第五乐章（张朝 曲） | 1–189 小节 | Adagio ♩=50 → 9 小节 Allegro ♩=162 → 173 小节 6/8 poco accel. → 188 小节 ♩.=♩ |

## 注意

- 谱上的 rit. 和 accel. 都没有写目标速度，页面上的默认目标速度是建议值，请按排练实际情况调整。
- 七彩之和 173 小节进 6/8 时，按八分音符不变计算（♩.=108）。188 小节 ♩.=♩，所以这里的 ♩ 等于渐快结束时的 ♩.；关掉渐快时是 ♩=108。
- 延长记号不处理。rubato 段仍然匀速。

## 修改与发布

整个页面就是一个文件：`index.html`。改完合并到 `main`，GitHub Pages 会自动重新发布。

---

## English

**Open it:** https://jingbincao.github.io/CCO-Rehearsal/

A rehearsal metronome for *Da Chao* (大潮) and *Qicai Zhi He* (七彩之和), Mvt. V "Red · Song of Fire". It clicks eighth notes that follow each bar's meter and grouping, so nobody has to count the mixed meters by hand.

### How to use

1. Pick a piece.
2. Enter a start bar. The tempo fills in from the score.
3. To change the tempo, use −/+, the slider, or type a number.
4. Press **Start**, or the Space bar.

### Sound and display

- **Downbeat of each bar**: the highest and loudest click.
- **First eighth of each group**: an accent, drawn as an eighth note.
- **Other eighths in the group**: soft subdivisions, drawn as eighth rests.
- Four bars are shown at once: the previous bar, the current one, and the next two. Each eighth lights up as it sounds.

### Grouping

- **Traditional meters** click in pairs of eighths: 4/4 = 2+2+2+2, 3/4 = 2+2+2, 2/4 = 2+2, 6/4 = 2+2+2+2+2+2.
- **Eighth-note meters** use the score's groupings: 10/8 = 3+3+2+2, 7/8 = 3+2+2, 5/8 = 3+2, 6/8 = 3+3, 8/8 = 2+2+2+2.

### Other features

- **Follow score tempo changes**: when a new tempo section starts, the tempo is converted at your current percentage of the score tempo.
- **Accel. & rit.**: optional even, per-eighth tempo ramps with editable targets.
- **End bar and loop**: for drilling a passage.
- **Clickable meter and tempo maps**: click any row to start there.

### Pieces

| Piece | Range | Tempo |
|---|---|---|
| Da Chao (Wang Yunfei) | bars 1–286 | ♩=96 → bar 33 ♩=152 → bar 123 ♩=66 rubato → bar 175 ♩=160 |
| Qicai Zhi He, Mvt. V (Zhang Zhao) | bars 1–189 | Adagio ♩=50 → bar 9 Allegro ♩=162 → bar 173 6/8 poco accel. → bar 188 ♩.=♩ |

### Notes

- The score gives no target tempo for rit. or accel. The defaults on the page are suggestions; adjust them in rehearsal.
- Qicai Zhi He bar 173 keeps the eighth note constant going into 6/8 (♩.=108). Bar 188 is ♩.=♩, so its quarter equals the ♩. reached at the end of the accel., or ♩=108 with the accel. turned off.
- Fermatas are ignored. Rubato sections stay steady.

### Editing

The whole page is one file, `index.html`. Merge changes into `main` and GitHub Pages republishes automatically.
