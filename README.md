# Neural_Oh!giri_Generator_v1

Pix2SeqとAutoEncoderを用いて画像から大喜利を生成するAIを作成しました

## 必要ライブラリ

numpy==1.23.4

matplotlib==3.6.2

tensorflow==2.10.0

scikit-learn==1.1.3

tqdm==4.64.1
 

## モデル, データのダウンロード

[画像のエンコーダ](URL)

[大喜利の生成器](URL)

[語彙データ](URL)

[Boketeの画像データ](URL)
(ダウンロード後解凍してください)

[Boketeの大喜利データ](URL)

[学習に使用したデータ]([URL](https://drive.google.com/file/d/1G6HkNVT-OX7mhvutLt7HYuIU_k0a9JWm/view?usp=share_link))

上記のデータをダウンロードして次のように配置してください

Neural_Oh-giri_Generator_v1

├ generate_boke.ipynb

├ dist_encoder.h5

├ dist_generator.h5

├ accepted_numbers.json

├ word_to_index.json

bokete_data.json

bokete_image

├ 4.jpg

├ 5.jpg

...

## 大喜利を生成する

generate_boke.ipynbを開き, 上から順に実行してください.
