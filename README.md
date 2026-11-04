
# Multilingual Rubik's Cube Notation & Translation Matrix

A universal structural dictionary mapping 3x3 and 4x4 Rubik's Cube notations, solve mechanics, and operational language patterns across English, Latin, Spanish, and Korean.

---

## 1. Action Matrix & Lexicon

| Category | English | Latin | Spanish | Korean |
| :--- | :--- | :--- | :--- | :--- |
| **Descriptive** | Corner piece | Segmentum angulare | Pieza de esquina | 코너 조각 (Koneo jogak) |
| **Descriptive** | Edge piece | Segmentum marginale | Pieza de arista | 엣지 조각 (Etji jogak) |
| **Descriptive** | Center cap | Tegeticula centralis | Tapa central | 센터 캡 (Senteo kaep) |
| **Coordination** | Execute the sequence | Ordinem exsequere | Ejecuta la secuencia | 공식을 실행하세요 |
| **Coordination** | Align the layers | Tabulata aequa | Alinea las capas | 층을 정렬하세요 |
| **Coordination** | Invert the movement | Motum inverte | Invierte el movimiento | 동작을 반대로 하세요 |
| **Rebuttal** | That creates parity | Hoc paritatem adfert | Eso crea paridad | 그것은 패리티를 유발합니다 |
| **Rebuttal** | The algorithm is wrong | Formula vitiosa est | El algoritmo es incorrecto | 공식이 틀렸습니다 |
| **Rebuttal** | Do not flip the corner | Noli angulum vertere | No gires la esquina | 코너를 트위스트하지 마세요 |

---

## 2. English Outer Face & Layer Rotations

### 3x3 & 4x4 Base Outer Faces (90° Clockwise)
* **U**: Up (Top Layer)
* **D**: Down (Bottom Layer)
* **L**: Left (Left Layer)
* **R**: Right (Right Layer)
* **F**: Front (Front Face Layer)
* **B**: Back (Back Face Layer)

### Rotational Modifiers
* **Prime (`'`)**: 90° Counter-Clockwise (e.g., `R'`, `U'`, `F'`)
* **Double (`2`)**: 180° Turn (e.g., `R2`, `U2`, `F2`)

### 4x4 Big Cube Double-Layer Moves (Wide Moves)
* Turning outer layer + adjacent inner slice simultaneously:
  * **Rw** / **r** (Right Wide)
  * **Uw** / **u** (Up Wide)
  * **Fw** / **f** (Front Wide)

---

## 3. Core Solve Algorithms (English Reference)

### 3x3 Muscle-Memory Triggers
* **The "Sexy Move" (Insertion):** `R U R' U'`
* **The Sune (OLL Cross Orientation):** `R U R' U R U2 R'`
* **T-Permutation (PLL Corner Swap):** `R U R' U' R' F R2 U' R' U' R U R' F'`

### 4x4 Parity Override Strings
* **OLL Parity (Flipped Edge Slice):** 
  `Rw2 B2 U2 Lw U2 Rw' U2 Rw U2 F2 Rw F2 Lw' B2 Rw2`
* **PLL Parity (Opposite Edge Swap):** 
  `r2 U2 r2 Uw2 r2 uw2`

---

## 4. Cross-Lingual Rotation Translations

When building algorithms inside different localized execution engines, substitute the face markers using this vector map:

| Axis Vector | English | Latin | Spanish | Korean |
| :--- | :--- | :--- | :--- | :--- |
| **Top Face** | **U** | **S** (*Superius*) | **A** (Arriba) | **위** (Wi / U) |
| **Bottom Face** | **D** | **I** (*Inferius*) | **B** (Abajo) | **아래** (Arae / D) |
| **Right Face** | **R** | **D** (*Dextrum*) | **D** (Derecha) | **오른쪽** (Oreunjjok / R) |
| **Left Face** | **L** | **S** (*Sinistrum*) | **I** (Izquierda) | **왼쪽** (Oenjjok / L) |
| **Front Face** | **F** | **A** (*Adversum*) | **F** (Frente) | **앞** (Ap / F) |
| **Back Face** | **B** | **P** (*Posticum*) | **T** (Atrás) | **뒤** (Dwi / B) |
| **Wide Modifier** | **w** | **l** (*Latum*, e.g., `Dl`) | **w** | **w** / **두 층** |
| **Counter-Clockwise** | **'** | **'** (*Inversum*) | **'** (Prima) | **'** (프라임) |

---

## 5. YouTube Tutorial Engine Mappings
* **General Notation Guide:** [SpeedCube US Notation Matrix](https://speedcube.us)
* **Virtual Rotational Sandbox:** [Cube Academy Dynamic Notation Engine](https://cube.academy)
