# 積分 (Integration)

## 定義

積分は微分の逆演算として定義されます。関数 f(x) の原始関数（不定積分）F(x) は、F'(x) = f(x) を満たす関数です。

$$\int f(x) dx = F(x) + C$$

ここで、C は積分定数です。

## 基本的な積分公式

### べき関数の積分

$$\int x^n dx = \frac{x^{n+1}}{n+1} + C \quad (n \neq -1)$$

$$\int \frac{1}{x} dx = \ln|x| + C$$

### 指数関数・対数関数の積分

$$\int e^x dx = e^x + C$$

$$\int a^x dx = \frac{a^x}{\ln a} + C \quad (a > 0, a \neq 1)$$

### 三角関数の積分

$$\int \sin x dx = -\cos x + C$$

$$\int \cos x dx = \sin x + C$$

$$\int \tan x dx = -\ln|\cos x| + C$$

## 積分の性質

### 線形性

$$\int [af(x) + bg(x)] dx = a\int f(x) dx + b\int g(x) dx$$

### 定数の積分

$$\int k dx = kx + C \quad (k \text{は定数})$$

## 基本例題

### 例題 1: べき関数

$$\int x^3 dx = \frac{x^4}{4} + C$$

### 例題 2: 一次関数

$$\int (10x - 5) dx = \int 10x dx - \int 5 dx = 5x^2 - 5x + C$$

### 例題 3: 二次関数

$$\int 3x^2 dx = 3 \cdot \frac{x^3}{3} + C = x^3 + C$$

### 例題 4: 多項式

$$\int (3t^2 + 6t) dt = \int 3t^2 dt + \int 6t dt = t^3 + 3t^2 + C$$

## 積分の計算手順

1. 被積分関数を確認する
2. 適切な積分公式を選択する
3. 線形性を利用して項ごとに積分する
4. 積分定数 C を忘れずに付ける
5. 必要に応じて検算（微分して元の関数になるか確認）

## 注意点

- 不定積分には必ず積分定数 C を付ける
- 積分できない関数も存在する
- 部分積分や置換積分などの高度な技法が必要な場合もある
