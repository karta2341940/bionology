<link rel="stylesheet" href="../index.css">

# 大腸桿菌(E.coli)埃西氏菌屬(Escherichia)

``` mermaid

graph TD
    Escherichia["大腸桿菌"]-->toxin1["Non-DEC(非腸道感染)"]
    Escherichia["大腸桿菌"]-->toxin2["DEC(腸道感染)"]
    toxin2-->sub1["非侵襲性(小腸感染)"]
    toxin2-->sub2["侵襲性"]
  
```


# 基本介紹
- 生化特徵<span class="red">IMViC</span>-> ++-- :吲哚(indole)反映、<span class="red">MV(MR-VP;M</span>ethyl red甲基紅，<span class="red">V</span>oges-Proskauer)、<span class="red">C</span>itrate檸檬酸鹽
- 感染：大多數感染是**__內源性__**的
- 預防、治療和控制
    - 正確烹飪<span class="red">牛肉</span>產品以降低EHEC感染的風險。
    - 保持高衛生標準，以降低暴露的風險。
    - 對不威脅生命的感染，一般都支持性治療。抗生素使用需參考體外藥敏感試驗結果。
```
IMViC -> ++--
indole(+)
Methyl red(+)
Voges(-)
Citrate(-)

- indole:分解色胺酸的產物
- 產生很多酸的話會使甲基紅變色
```

## 非腸道感染
- <span class="red">UPEC</span>(尿道致病性大腸桿菌,Uropathogenic E.coli)
    - 黏附素：<span class="red">PAP</span>菌毛(腎盂腎炎相關菌毛,pyelonephriti associated pi)
- NMEC(新生兒撓膜炎大腸桿菌,Neonatal meningitis E.coli)
    - <span class="red">莢膜K1</span>
## 腸道感染
### 非侵襲性
Watery diarrhea 吸附素與分泌性毒素為媒介
- ETEC 腸產毒性大腸桿菌 Enterotoxigenic
    - 吸附素：CFA
    - 毒素：ST、LT
- EAEC 腸聚集性大腸桿菌 Enteroaggregative
    - 吸附素：生物膜
    - 毒素：EAST
```markdown
Entero--- 腸道---
---toxigenic ---產毒素的
---aggregative ---聚集的
```
### 侵襲性
- <span class="red">EHEC</span>腸出血性大腸桿菌 Enterohemorrhagic
    - <span class="red">O157H7;牛肉;HUS Sorbitol MAC(-)</span>(Sorbital不分解)
        - 吸附素：非菌毛黏附素
        - 毒素：<span class="red">類志賀毒素Stx</span>
- EPEC 腸致病性大腸桿菌 Enteropathogenic 
    - 吸附素：
    - 質體：BFP
    - 致病島：Intimin,Tur,T3SS-A/E
- EIEC 腸侵襲性大腸桿菌 Enteroinvasive
    - 吸附：非菌毛黏附素T3SS，類似[Listeria](# "李斯特菌")





## 大腸桿菌共通點
- 吸附素：Type 1 pili (common pili) : 結合甘露糖
- 毒素：[Endotoxin]( # "內毒素")
- 侵襲素：Enterochelin ( iron chelator )

