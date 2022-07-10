## EDS例句

```
# 22047013
That's not fair; they are not all fat.

# 22025011
We don not need cartoons anymore.

# 22025006
He declined to elaborate.

# 22023015 (unknown jewelery)
The jewelery chain was put up for sale in June.

# 20031013
Mr. Keating, for his part, has filed suit alleging that regulators unlawfully seized the thrift. 

# 22040008
Citicorp yesterday reported a 9% third-quarter earnings drop, which analysts called a bit disappointing, while Manufacturers Hanover Corp. posted a $789 million loss for the quarter after adding $950 million to its reserve for loans to less-developed countries.

# 22013100
Dade County and federal authorities, learning that he intended to fly through Miami, made plans to arrest him on the gun running charges as soon as he hit U.S. soil.

# 22055002
George L. LaMore, president and chief executive officer, will become chairman and chief executive upon Mr. Cunin's retirement.

# 22083010
In New York Stock Exchange composite trading, shares of the Akron, Ohio-based company fell $1.375 to $49.125.

# 22095004
In a Securities and Exchange Commission filing, BroadBeach said it sold the 101,000 McGill shares for $7.3 million in a private transaction on Oct. 12.

# 22064025
A U.S. decision to refuse the IMF its capital increase, or limit it to 25%, would bring a major change in international economic policy, and could not be taken lightly.



Mr. Keating , for his part , has filed suit alleging that regulators illegally seized the savings .

This boy likes smiling .

Shearson also has been an aggressive participant in the leveraged buy-out business.
```

## AMR例句

```
高科技产业应实现“顶天立地”。
科技“顶天”，市场“立地”。
感谢敢于披露“腐败发票”的正义人士！！！！！
这就是所谓的“自古英雄出少年”。 
哪个国家都有小偷、流氓、变态； 
2007年1月9日，省国土厅批复同意德卡公司用地预审申请。 
同年，德卡公司按县政府要求，投入近4000万元兴建了县人民医院。 
法院应该“以实事为依据，以法律为准绳”,做出公平公正的判决。（并不好）
很显然，中国的高房价已使民怨沸腾，再不进行有效、有力调控，就会中国社会稳定带来灾难性的严重后果。 
香港的深圳“唯冠”诉苹果手机侵犯其抢注的商标权，在上海浦东法院被驳回。
为了小孩今后的继续教育不受限制，两年后全家移民到美国去了。 
```

```
# ::id export_amr.22 ::2017-02-10 16:39:42
# ::snt 感谢 敢于 披露 “ 腐败 发票 ” 的 正义 人士 ！！！！！ 
# ::wid x1_感谢 x2_敢于 x3_披露 x4_“ x5_腐败 x6_发票 x7_” x8_的 x9_正义 x10_人士 x11_！！！！！ x12_ 
(x1 / 感谢-02
      :arg1()  (x10 / 人士
            :arg0-of(x8/的)  (x2 / 敢于-01
                  :arg1()  (x3 / 披露-01
                        :arg1()  (x6 / 发票
                              :mod()  (x5 / 腐败))))
            :arg0-of()  (x9 / 正义-01))
      :mode()  (x11 / expressive))
      
# ::id export_amr.278 ::2018-03-30 16:33:29
# ::snt 这 就 是 所谓 的 “ 自古 英雄 出 少年 ” 
# ::wid x1_这 x2_就 x3_是 x4_所谓 x5_的 x6_“ x7_自古 x8_英雄 x9_出 x10_少年 x11_” x12_ 
(x9 / 出-04
      :time()  (x7 / 自古)
      :arg1-of(x5/的)  (x4 / 所谓-01)
      :domain(x3/是)  (x23 / thing
            :mod()  (x1 / 这))
      :mod()  (x2 / 就)
      :arg0()  (x8 / 英雄)
      :arg1()  (x10 / 少年))

# ::id export_amr.1415 ::2018-04-11 21:26:02
# ::snt 哪 个 国家 都 有 小偷 、 流氓 、 变态 ； 
# ::wid x1_哪 x2_个 x3_国家 x4_都 x5_有 x6_小偷 x7_、 x8_流氓 x9_、 x10_变态 x11_； x12_ 
(x5 / 有-03
      :arg0()  (x3 / 国家
            :cunit()  (x2 / 个)
            :mod()  (x4 / 都)
            :mod()  (x1 / 哪))
      :arg1()  (x20 / and
            :op1()  (x6 / 小偷)
            :op2()  (x8 / 流氓)
            :op3()  (x10 / 变态)))
            
# ::id export_amr.1425 ::2017-01-05 14:43:08
# ::snt 2007年 1月 9日 ， 省 国土厅 批复 同意 德卡 公司 用地 预审 申请 。 
# ::wid x1_2007年 x2_1月 x3_9日 x4_， x5_省 x6_国土厅 x7_批复 x8_同意 x9_德卡 x10_公司 x11_用地 x12_预审 x13_申请 x14_。 x15_ 
(x16 / and
      :op1()  (x7 / 批复-01
            :arg0()  (x33 / government-organization
                  :name()  (x5_x6 / name :op1 x5/省  :op2 x6/国土厅 ))
            :arg1()  (x13 / 申请
                  :arg1()  (x12 / 预审-01
                        :arg1()  (x11 / 用地
                              :arg0()  (x10 / 公司
                                    :name()  (x9 / name :op1 x9/德卡 ))))))
      :op2()  (x8 / 同意-01
            :arg0()  (x33 / government-organization)
            :arg1()  (x13 / 申请))
      :time()  (x29 / date-entity
            :year()  (x1 / 2007)
            :month()  (x2 / 1)
            :day()  (x3 / 9)))


# ::id export_amr.1426 ::2017-01-05 14:45:37
# ::snt 同 年 ， 德卡 公司 按 县 政府 要求 ， 投入 近 4000万 元 兴建 了 县 人民 医院 。 
# ::wid x1_同 x2_年 x3_， x4_德卡 x5_公司 x6_按 x7_县 x8_政府 x9_要求 x10_， x11_投入 x12_近 x13_4000万 x14_元 x15_兴建 x16_了 x17_县 x18_人民 x19_医院 x20_。 x21_ 
(x11 / 投入-02
      :arg0()  (x5 / 公司
            :name()  (x4 / name :op1 x4/德卡 ))
      :arg1()  (x26 / monetary-quantity
            :quant()  (x12 / 近
                  :op1()  (x13 / 40000000))
            :unit()  (x14 / 元))
      :arg2()  (x15 / 兴建-01
            :aspect()  (x16 / 了)
            :arg0()  (x5 / 公司)
            :arg1()  (x43 / facility
                  :name()  (x17_x18_x19 / name :op1 x17/县  :op2 x18/人民  :op3 x19/医院 )))
      :manner()  (x6 / 按-02
            :arg1()  (x9 / 要求-04
                  :arg0()  (x40 / government-organization
                        :name()  (x7_x8 / name :op1 x7/县  :op2 x8/政府 )))
            :arg0()  (x5 / 公司))
      :time()  (x1_x2 / 同年))
      
# ::id export_amr.42 ::2018-03-21 16:32:42
# ::snt 法院 应该 “ 以 实事 为 依据 ， 以 法律 为 准绳 ” , 做出 公平 公正 的 判决 ， 
# ::wid x1_法院 x2_应该 x3_“ x4_以 x5_实事 x6_为 x7_依据 x8_， x9_以 x10_法律 x11_为 x12_准绳 x13_” x14_, x15_做出 x16_公平 x17_公正 x18_的 x19_判决 x20_， x21_ 
(x2 / 应该-02
      :arg0()  (x15 / 做出-01
            :arg0()  (x1 / 法院)
            :arg1()  (x19 / 判决-01
                  :arg0-of(x18/的)  (x17 / 公正-01)
                  :arg0-of()  (x16 / 公平-01)
                  :arg0()  (x1 / 法院))
            :manner()  (x4_x6 / 以为-03
                  :arg1()  (x5 / 实事)
                  :arg2()  (x7 / 依据-01)
                  :arg0()  (x1 / 法院))
            :manner()  (x9_x11 / 以为-03
                  :arg1()  (x10 / 法律)
                  :arg2()  (x12 / 准绳)
                  :arg0()  (x1 / 法院))))
                  
# ::id export_amr.156 ::2018-03-27 13:50:32
# ::snt 很 显然 ， 中国 的 高 房价 已 使 民怨 沸腾 ， 再 不 进行 有效 、 有力 调控 ， 就 会 中国 社会 稳定 带来 灾难性 的 严重 后果 。 
# ::wid x1_很 x2_显然 x3_， x4_中国 x5_的 x6_高 x7_房价 x8_已 x9_使 x10_民怨 x11_沸腾 x12_， x13_再 x14_不 x15_进行 x16_有效 x17_、 x18_有力 x19_调控 x20_， x21_就 x22_会 x23_中国 x24_社会 x25_稳定 x26_带来 x27_灾难性 x28_的 x29_严重 x30_后果 x31_。 x32_ 
(x2 / 显然
      :degree()  (x1 / 很)
      :arg0()  (x36 / and
            :op2()  (x43 / condition
                  :arg1(x13/再)  (x15 / 进行-01
                        :arg1()  (x19 / 调控-01
                              :arg1()  (x7 / 房价
                                    :arg0-of()  (x6 / 高-01)
                                    :poss(x5/的)  (x57 / country
                                          :name()  (x4 / name :op1 x4/中国 )))
                              :arg0-of()  (x16 / 有效-01)
                              :arg0-of()  (x18 / 有力-01))
                        :polarity()  (x14 / -))
                  :arg2(x21/就)  (x22 / 会-02
                        :arg0()  (x26 / 带来-01
                              :arg1()  (x30 / 后果
                                    :mod(x28/的)  (x27 / 灾难性)
                                    :arg0-of()  (x29 / 严重-01))
                              :arg2()  (x25 / 稳定-01
                                    :arg1()  (x24 / 社会
                                          :mod()  (x23 / x57))))))
            :op1()  (x9 / 使-01
                  :aspect()  (x8 / 已-01)
                  :arg0()  (x7 / 房价)
                  :arg2()  (x10 / 民怨)
                  :arg2()  (x11 / 沸腾-01
                        :arg0()  (x10 / 民怨)))))
                        
# ::id export_amr.190 ::2018-03-27 21:23:32
# ::snt · 香港 的 深圳 “ 唯冠 ” 诉 苹果 手机 侵犯 其 抢注 的 商标权 ， 在 上海 浦东 法院 被 驳回 。 
# ::wid x1_· x2_香港 x3_的 x4_深圳 x5_“ x6_唯冠 x7_” x8_诉 x9_苹果 x10_手机 x11_侵犯 x12_其 x13_抢注 x14_的 x15_商标权 x16_， x17_在 x18_上海 x19_浦东 x20_法院 x21_被 x22_驳回 x23_。 x24_ 
(x22 / 驳回-01
      :location(x17/在)  (x20 / 法院
            :location()  (x42 / local-region
                  :name()  (x19 / name :op1 x19/浦东 )
                  :location()  (x43 / city
                        :name()  (x18 / name :op1 x18/上海 ))))
      :arg1()  (x8 / 诉-01
            :arg1()  (x11 / 侵犯-01
                  :arg0()  (x10 / 手机
                        :name()  (x9 / name :op1 x9/苹果 ))
                  :arg1()  (x15 / 商标权
                        :arg1-of(x14/的)  (x13 / 抢注
                              :arg0()  (x12 / x44))))
            :arg0()  (x44 / company
                  :name()  (x4_x6 / name :op1 x4/深圳  :op2 x6/唯冠 )
                  :location(x3/的)  (x49 / country-region
                        :name()  (x2 / name :op1 x2/香港 )))))
                        

```

参考：

https://github.com/hankcs/HanLP/blob/doc-zh/plugins/hanlp_demo/hanlp_demo/zh/amr_stl.ipynb

https://github.com/GoThereGit/Chinese-AMR 中文AMR比赛

