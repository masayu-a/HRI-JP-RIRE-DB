# HRI-JP NINJAL 経路情報参照表現データベース (HRI-JP NINJAL Route Information Reference Database: HRI-JP RIRE DB)

## Description

地図中の2地点の情報を刺激として呈示し、その経路情報を相対参照情報のみで記述したもの。記述内容について (X: 始点の説明、Y: 経路の説明、Z: 終点の説明)などの分類を人手で付与するとともに、一般の方が評定した「わかりやすさ」の情報を付与した。

## Features

- map-original/ 「わかりやすさ」評定収集時に呈示した地図
- map-rotated/ 経路情報参照表現収集時に呈示した地図
- descrpition-rating.txt
  1. 地図画像
  2. 参照表現
  3. 「わかりやすさ」評定平均値
  4. ABC (相対位置情報表現のみ (A) か否 (B)か)
  5. W 経路を反対方向に説明 (0: false, 1: true)
  6. X 始点の詳細な説明がある (0: false, 1: true)
  7. Y 経路の詳細な説明がある (0: false, 1: true)
  8. Z 終点の詳細な説明がある (0: false, 1: true)

## Creators

- 浅原 正幸 (国立国語研究所)
- 川端 良子 (国立国語研究所)
- 大村 舞 (国立国語研究所)
- 小西 光 (Tecca 合同会社)
- 竹内 誉羽 (ホンダリサーチインスティテュート)

## References

- 川端 良子・大村 舞・小西 光・浅原 正幸・竹内 誉羽 (2024)「地図を刺激に用いた経路情報参照表現の収集」第30回言語処理学会年次大会(NLP2024)

## License

CC BY-NC-SA 4.0 

## Credit

本データは、ホンダリサーチインスティテュート-国立国語研究所共同研究プロジェクト
「曖昧な参照表現による目的地設定対話システム」(2023年度)による。

## Contact

masayu-a@ninjal.ac.jp
