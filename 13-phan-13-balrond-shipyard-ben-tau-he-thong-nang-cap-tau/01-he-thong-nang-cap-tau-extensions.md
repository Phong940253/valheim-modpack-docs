# ⚓ Hệ Thống Nâng Cấp Tàu (Extensions)

Bảng tổng hợp nâng cấp theo tàu. Mỗi nâng cấp cần **Bản Vẽ (Schematic)** chế tạo tại **Bàn Biên Tập** + nguyên liệu.

| Extension | Raft | Karve | Knarr | Snekke | Drakkar (Longship) | Holk | Ashlands Drakkar |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **Shield** | — | ✓<br>+200 HP | ✓<br>+200 HP | ✓<br>+200 HP | ✓<br>+300 HP | ✓<br>+300 HP | ✓<br>+300 HP |
| **Lamp** | — | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| **Anchor** | — | ✓ | ✓ | ✓ | — | — | — |
| **Tent** | — | — | ✓<br>+100 HP | ✓<br>+100 HP | ✓<br>+300 HP | ✓<br>+200 HP | ✓<br>+200 HP |
| **Armor** | — | ✓<br>+100 HP<br>pierce immune | ✓<br>+100 HP<br>pierce immune | ✓<br>+100 HP<br>pierce immune | ✓<br>+200 HP<br>pierce immune | ✓<br>+200 HP<br>pierce immune | — |
| **Supply/Barrels/Crates** | — | ✓ +100 HP blunt | ✓ +100 HP blunt | ✓ +100 HP blunt | Barrels +100 blunt<br>Crates +100 slash | ✓ +200 HP blunt | ✓ +200 HP blunt |
| **Oars** | — | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| **Ropes** | — | — | — | — | — | ✓ | ✓ |
| **NamePlate** | — | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| **SailColors** | — | ✓ 10 colors | ✓ 10 colors | ✓ 10 colors | ✓ 10 colors | ✓ 10 colors | ✓ 10 colors |

#### ❤️ Công Thức Tính HP

`totalHP = baseHP + shield + tent + ram + supply + armor`

`totalMass = baseMass + (shield + tent + ram + supply) / 2`

Comfort: base=1, shield+1, tent+1, light+1 (max=3)

#### 🚣 Thống Số Mái Chèo (Oars)

| Tàu | Rudder Speed | Steer Force | Paddle Force |
| --- | --- | --- | --- |
| **Karve** | 1.1 | 0.3 | 0.5 + 0.25×(players-1), max 3.0 |
| **Knarr** | 2.3 | 0.2 | 0.5 + 0.25×(players-1), max 3.0 |
| **Snekke** | 2.3 | 0.2 | 0.5 + 0.25×(players-1), max 3.0 |
| **Drakkar (Longship)** | 1.1 | 1.1 | 0.5 + 0.25×(players-1), max 3.0 |
| **Holk** | 1.1 | 1.65 | 0.5 + 0.25×(players-1), max 3.0 |
| **Ashlands Drakkar** | 1.1 | 1.1 | 0.5 + 0.25×(players-1), max 3.0 |
