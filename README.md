# NAS技術調査
指動作識別アルゴリズム作成に向けてNASの技術調査  

# 1. 背景ーNASとは
Neural Architecture Searchの略  
従来、人の勘、経験に依存していたDeep Learningのネットワーク設計を自動で探索するアルゴリズムの総称。  
<img width="290" alt="スクリーンショット 2022-01-16 10 32 04" src="https://user-images.githubusercontent.com/60390051/149643881-554ba88c-02b6-4888-b49f-4c2bfb54bfc7.png">

# 2. 調査手法
今回調査した論文は以下の通り  
[A comprehensive Suvey of Neural Architecture Search: Challenges and Solutions(2020.8)](https://arxiv.org/abs/2006.02903)  
従来のsurvey論文と異なり、ただ手法＋精度を羅列するのではなく、NASの課題と解決策に焦点を当てたsurvey論文

# 3. 調査内容
「課題⇨解決策」の主題は４つ
1. Global search space -> Modulra search space
2. Discrete search strategy -> Continuous search strategy
3. Search from scratch -> Neural architecture recycling
4. Fully trained -> Incomplete training

## 3.1. NASの研究領域
NASには大きく分けて3つの調査領域がある
1. 探索空間の決定  
2. 探索手法の決定    
3. 評価戦略の決定 ↑ここまでが従来のsurveyのまとめ方   

4. 最適化戦略の決定  

## 3.2. 探索空間の決定  

## 3.3. 探索手法の決定  
1. Reinforcement Learning  
2. Evolution Algorithm  
3. Gradient Optimization  
4. Random Search  
5. Sequential Model-based Optimization(SMBO)  


## 3.4. 最適化戦略の決定
1. Modular search space  
2. Continuous search strategy  
3. Neural architecture recycling  
4. Incomplete training  
