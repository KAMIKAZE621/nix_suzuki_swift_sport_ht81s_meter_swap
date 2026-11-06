# Suzuki Swift Sport HT81S Monster M18 Turbo (`nix_suzuki_swift_sport_ht81s_meter_swap`)

Assetto Corsa 用の **スズキ スイフトスポーツ (HT81S) モンスター M18 ターボ・カスタム仕様** MOD です。

---

## 📥 ダウンロード & 導入方法 (Content Manager 対応)

以下のリンクから配布用アーカイブ（`.7z`）を直接ダウンロードできます：

### 👉 **[`nix_suzuki_swift_sport_ht81s_meter_swap.7z` をダウンロード (Latest Release v1.04)](https://github.com/KAMIKAZE621/nix_suzuki_swift_sport_ht81s_meter_swap/releases/latest/download/nix_suzuki_swift_sport_ht81s_meter_swap.7z)**
*（または右側の **[Releases](https://github.com/KAMIKAZE621/nix_suzuki_swift_sport_ht81s_meter_swap/releases)** ページからダウンロードしてください）*

### インストール手順
1. **Content Manager を使用する場合（推奨）**:
   - ダウンロードした **`nix_suzuki_swift_sport_ht81s_meter_swap.7z`** を、そのまま **Content Manager のウィンドウへドラッグ＆ドロップ** し、右上のメニュー（緑色のアイコン）から **Install** をクリックしてください。
2. **手動で配置する場合**:
   - `.7z` を解凍し、`nix_suzuki_swift_sport_ht81s_meter_swap` フォルダを以下のディレクトリへ配置してください：
     ```text
     assettocorsa/content/cars/nix_suzuki_swift_sport_ht81s_meter_swap
     ```

---

## 主要スペック

| 項目 | 仕様 |
| :--- | :--- |
| **車両名** | Suzuki Swift Sport HT81S Monster M18 Turbo |
| **エンジン** | Monster Sport 1.8L (1,770cc) 鍛造ローコンプピストンキット + ボルトオンターボ & インタークーラー |
| **最高出力 / 最大トルク** | 250 bhp / 300 Nm |
| **車重 / パワーウェイトレシオ** | 930 kg / 3.72 kg/HP |
| **最高速度 / 0-100km/h 加速** | 235 km/h / 5.1 s |
| **駆動方式 / トランスミッション** | FF (FWD) / 純正クロス 5MT + 1.5way 機械式 LSD |

---

## 主なカスタム・改造内容

1. **パワートレイン & エキゾースト**
   - モンスタースポーツ製 1.8L 鍛造ローコンプピストンキット＋カスタムターボ仕様
   - 柿本改チタンテールマフラー装備
   - 強化ブレーキシステム・1.5way 機械式 LSD 搭載
2. **メーター・インジケータースワップ (`extension/`)**
   - カスタムメーター & インジケーター構成（Strada 7 / 専用インジケーター KN5・Lua スクリプト連携）
3. **サスペンション & アライメント刷新 (`data/suspensions.ini`, `data/setup.ini`)**
   - リアサスペンションをリジッドアクスル (`AXLE`) からマクファーソンストラット (`STRUT`) へ構造変更
   - バネレート最適化（Front: `42,000 N/m` / Rear: `26,000 N/m`）およびスタビライザー強化（Front: `18,000` / Rear: `10,000`）
   - ピット画面での前後キャンバー角・トー角のフル調整に対応
4. **エクステリア 3D モデル改修 (`suzuki_swift_sport_ht81s.kn5`)**
   - **JDM リアバンパーカット**: 平面バイセクト切断（$Y = 0.480\text{m}$）による直線断面加工
   - **スペアタイヤパン造形追加**: トランク床下にマットブラックのプレス加工スペアタイヤウェル（`SPARE_TIRE_PAN`）を追加し、下回りからの室内透けを防止

---

## クレジット

- **Base Mod Author**: Nix_Dektara
- **Special Thanks**: Zao michiko, Ulla Lorentz, Minami Shin, Kijima Lear
