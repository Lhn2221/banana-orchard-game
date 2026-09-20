# Asset provenance

Downloaded 2026-09-13. External model files are bundled locally; gameplay does not hotlink model hosts.

| Local file | Creator / source | License | Adaptation |
| --- | --- | --- | --- |
| public/assets/apple.glb | User's Astra_Test/Apple.blend and packed Apple_Skin_Texture.png | User-supplied; not represented as CC0 | Exported the existing body, stem and leaf to GLB. Source file is unchanged. |
| public/assets/monkey.glb | [Monkroose by Quaternius](https://poly.pizza/m/j4rVPvxyLg) | CC0 1.0, as stated on the model page | Runtime brown recoloring, scale, formation and included run animation; stylized monkey creature |
| public/assets/banana.glb + Textures/colormap.png | [Food Kit 2.0 by Kenney](https://kenney.nl/assets/food-kit) | CC0; bundled Kenney-Food-License.txt | Runtime blue/rainbow material variants |
| public/assets/tree.glb | [Nature Kit 2.1 by Kenney](https://kenney.nl/assets/nature-kit), tree_default.glb | CC0; bundled Kenney-Nature-License.txt | Runtime scale and placement |
| public/assets/fence.glb | [Nature Kit 2.1 by Kenney](https://kenney.nl/assets/nature-kit), fence_planks.glb | CC0; bundled Kenney-Nature-License.txt | Runtime scale and placement |
| public/assets/crown.glb | [Crown by Quaternius](https://poly.pizza/m/i0PZVuVlYv) | CC0 1.0 on the model page | Positioned on the stage-five apple boss; downloaded 2026-09-14 |
| public/assets/monkey-thumbs-up.png | [Monkey by Schade / ClipSafari](https://www.clipsafari.com/clips/o247295-monkey) | CC0, as stated on the download page | Legacy unused illustration; replaced by game-model portrait |

The victory portrait renders the existing Quaternius monkey with its included Wave animation and adjusted finger pose; no new character geometry is created. Energy-ball leaves reuse the existing leaf mesh inside the user's apple GLB. The enclosing transparent sphere and explosion ring are gameplay effects, not newly modeled props. Golden/rainbow monkeys reuse Quaternius geometry and animation with runtime materials. Stage colors multiply the original Kenney materials. All images/models are served locally.

CC0 reference: https://creativecommons.org/publicdomain/zero/1.0/

Google Fonts provides Jua and Noto Sans KR through its CSS service (SIL Open Font License). The interface falls back to system fonts when unavailable. Three.js and Vite licenses remain in their npm packages. No newly modeled character, weapon, tree or fence is used; the flat ground and math gates are gameplay geometry.


## Shop skins (2026-09-15)

- public/assets/holiday/candy.glb and holiday/Textures/colormap.png: Kenney Holiday Kit 2.0 candy-cane-red, CC0. https://kenney.nl/assets/holiday-kit . License bundled as Kenney-Holiday-License.txt. Scaled and placed in tree positions.
- public/assets/coconut.glb: Kenney Food Kit 2.0 coconut, CC0. Uses existing Food Kit texture and license. Recolored for weapon tiers.
- public/assets/rabbit.glb: Rabbit by Quaternius, CC0: https://poly.pizza/m/mKev485XTR . Includes run animation; runtime scaling and rank recoloring. Existing geometry, no new modeling.
- Shop preview images are rendered locally from these models.
