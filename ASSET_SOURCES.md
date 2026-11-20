# 美术来源与使用边界

本轮日期：2026-11-15。以下是查阅入口及改编说明，不构成对原作形象的独占授权声明。

## 新绘素材

`assets/hero-*.svg` 共 12 张，由 `tools/draw-hero-portraits.cjs` 中的原创几何路径绘制。头像、服装、咒具和材质细节按角色特征重新组织成小尺寸赛璐璐造型。没有描摹、嵌入或热链官方网站的 PNG/JPG，也未使用他人同人插画。

角色本身仍归原著及相关权利人。形象出处：

- 《咒术回战》：芥见下下／集英社；动画视觉参考为《咒术回战》制作委员会公开角色设定。
- 《无职转生》：理不尽な孫の手／MF Books；插画角色设计及动画形象权利归相应权利人。

`combat-vfx.js`、`vfx-style.js` 及相关 Canvas 路径为项目本地绘制，不依赖第三方粒子贴图、音频样本或远程素材。可选打击音使用浏览器振荡器即时合成。

## 本轮实际访问的官方参考

| 入口 | 核对用途 | 使用方式 |
|---|---|---|
| https://jujutsukaisen.jp/character/category4.php | 真人、漏瑚、花御、陀艮等外形与服饰 | 浏览官方设定图与角色列表，只作视觉参考 |
| https://jujutsukaisen.jp/character/index.php | 虎杖、乙骨、秤等角色列表、公开人物说明 | 查阅列表、人物描述和设定图入口 |
| https://jujutsukaisen.jp/episodes/39.php | 陀艮领域与甚尔登场剧情 | 查阅官方剧情梗概 |
| https://mushokutensei.jp/character/ | 鲁迪乌斯、龙神身份与角色时代版本 | 查阅人物简介和公开服装设定 |

浏览器中还查看了 `chara_category4/chara_detail2.png`、`chara_detail3.png`、`chara_detail4.png` 和《无职转生》鲁迪乌斯公开设定图。它们未被复制到本项目素材目录或成品压缩包。某些官网页面使用图片呈现文字；没有从未读到的页面杜撰设定。

## 原作依据与游戏假设

- 宿傩采用伏黑受肉的黑发、咒纹与和服配置，便于解释本作沿用的十种影法术与魔虚罗。未将四臂完全受肉与此造型混为同一时刻。
- 五条采用经典黑眼罩、高领制服；能力使用本篇招式合集。这是形象与玩法的合并呈现，不是某一页漫画的逐格复刻。
- 甚尔使用不同时期的咒具合集。零咒力的识别例外和无咒力物体仍会被御厨子斩击的区别用于修正旧规则；咒具距离、抑制时长、伤害与移动爆发属于游戏数值。
- 更精细的领域能够压过较低精度领域。程序中的 2–5 档位是对这一机制的保守近似，不是原作公布的战力值；精度接近时仍在重叠区抵消必中。
- 《无职转生》原作为轻小说，不能将其动画外形与本作压缩的魔力系统称为“漫画逐格还原”。预知眼不赋予移动 AI；乱魔只针对指定魔术，不扩展为跨作品消除一切。
- 本次没有取得付费漫画、小说完整正文，也未声称逐页重新核验；详细能力定位继续参见已有三英雄、七英雄资料说明。

## 继承素材

其他 `assets/*.png` 和旧版 SVG 是既有项目素材，包括用户此前提供的图片。它们保持原状，来源不全者不新增授权声明。新增英雄入口均指向 `hero-*.svg`，旧版英雄图片仅为历史兼容保留。

## 42 人对战版特效

出招、命中和残影叠加在项目的 Canvas 绘制上。内嵌特效图集使用 Kenney / Kenney Vleugels 的 CC0 1.0 蒙版，来自 [Particle Pack](https://kenney.nl/assets/particle-pack)、[Smoke Particles](https://kenney.nl/assets/smoke-particles)、[Splat Pack](https://kenney.nl/assets/splat-pack)、[Foliage Sprites](https://kenney.nl/assets/foliage-sprites) 和 [Light Masks](https://kenney.nl/assets/light-masks)。

咒术角色的技能轮廓参考 [VIZ 原作目录](https://www.viz.com/read/manga/jujutsu-kaisen/all) 和 [Bandai Namco 官方资料](https://www.bandainamcoent.com/games/jujutsu-kaisen-cursed-clash)，按游戏现有事件抽象绘制。
