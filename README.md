<img width="800" alt="H M" src="https://user-images.githubusercontent.com/58076642/160087250-eb088ce0-4c0e-41c9-b893-50d911b12738.png">


# Kaggle_H&M-Personalized-Fashion-Recommendations 

## コンペの目的  
training data期間の直後の7日間に各顧客が購入するものを予測する。  
12個まで予測することが可能  

## 評価指標
Mean Average Precision @ 12 (MAP@12)  
今回のコンペにおいては対象ユーザーに対する12位までの予測に対するAPの平均値を指す  
<img width="500" alt="MAP" src="https://user-images.githubusercontent.com/58076642/160090369-712c9c43-cced-4bee-8a75-cfc2a4b13cff.png">  

※AP(Average Precision):その順位までにおける正解率を、各正解のデータの部分に限定して平均をとったもの

評価指標の解釈notebook by渡部くん  
https://www.kaggle.com/code/ano12pmo/map-12  

## Overview  
H&M Group is a family of brands and businesses with 53 online markets and approximately 4,850 stores. Our online store offers shoppers an extensive selection of products to browse through. But with too many choices, customers might not quickly find what interests them or what they are looking for, and ultimately, they might not make a purchase. To enhance the shopping experience, product recommendations are key. More importantly, helping customers make the right choices also has a positive implications for sustainability, as it reduces returns, and thereby minimizes emissions from transportation.

In this competition, H&M Group invites you to develop product recommendations based on data from previous transactions, as well as from customer and product meta data. The available meta data spans from simple data, such as garment type and customer age, to text data from product descriptions, to image data from garment images.

There are no preconceptions on what information that may be useful – that is for you to find out. If you want to investigate a categorical data type algorithm, or dive into NLP and image processing deep learning, that is up to you.

(deepl)  

H&Mグループは、53のオンラインマーケットと約4,850の店舗を持つ、ブランドとビジネスのファミリーです。オンラインストアでは、買い物客に豊富な品揃えの中から好きなものを選んでもらうことができます。しかし、選択肢が多すぎると、お客様は興味のあるものや探しているものをすぐに見つけることができず、最終的に購入に至らないこともあります。ショッピング体験を向上させるためには、商品のレコメンデーションが重要な鍵となります。さらに重要なことは、お客様の正しい選択を支援することは、返品を減らし、それによって輸送に伴う排出を最小限に抑えるという、サステナビリティにも良い影響を与えるということです。

このコンペティションでは、H&Mグループが、過去の取引データ、および顧客と商品のメタデータに基づく商品推奨を開発するよう、皆様にお願いしています。メタデータは、衣服の種類やお客様の年齢などの単純なデータから、商品説明のテキストデータ、衣服画像の画像データまで幅広く用意されています。

どのような情報が有用であるかという先入観はなく、それはお客様自身が調べることです。カテゴリーデータ型のアルゴリズムを調べたり、NLPや画像処理のディープラーニングに飛び込んでみたり、それはあなた次第です。

www.DeepL.com/Translator（無料版）で翻訳しました。

