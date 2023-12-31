# 百度百科 500 万数据集

```py
In [1]: !7z x baidu_wiki_500w_part1.7z

7-Zip 19.00 (x64) : Copyright (c) 1999-2018 Igor Pavlov : 2019-02-21

Scanning the drive for archives:
1 file, 48579917 bytes (47 MiB)

Extracting archive: baidu_wiki_500w_part1.7z
--
Path = baidu_wiki_500w_part1.7z
Type = 7z
Physical Size = 48579917
Headers Size = 180
Method = LZMA:26
Solid = -
Blocks = 1

Everything is Ok

Size:       175163873
Compressed: 48579917

In [2]: open('baidu_wiki_500w_part1.jsonl', encoding='utf8').readline()
Out[2]: '{"title": "红色食品", "summary": "红色食品是指食品为红色、橙红色或棕红色的食品。科学家认为，多吃些红色食品可预防感冒。红 色食品有红柿椒、西红柿、胡萝卜、红心白薯、红果（山楂）、红苹果、草莓、红枣、老南瓜、红米、柿子等。 有治疗缺铁性贫血和缓解疲劳的作 用，对乳腺癌等肿瘤疾病有防治作用，给人以兴奋感，有增加食欲，光洁皮肤，增强表皮细胞再生和防止皮肤衰老，预防感冒等作用。", "sections": [{"title": "简介", "content": "红色食品富含番茄红素、胡萝卜素、铁和部分氨基酸，是优质蛋白质、碳水化合物、膳食纤维、B族维生素和 多种无机盐的重要来源，可以弥补粳米、白面中的营养缺失。经常食用红色食品，可以进一步提高对主食中营养的利用率，山植等食品还有治疗癌症的功效。被称为“红色生力军。”营养学家认为，红色蔬果最典型的优势在于它们都是富含天然铁质的食物，例如我们常吃的樱桃、大枣等都是贫血患者的天然良药，也适合女性经期失血后的滋补。所以，红色蔬果，女人尽可放心多吃。红色食品中还含有致病微生物的“杀手”——巨噬细胞，可以有效地抵御感冒病毒等微生物，增强人体抵抗感冒的能力。\xa0\xa0红色食品\\n在所有的果蔬当中，名声最好的莫过于苹果。西方有“One apple a day，keeps the doctors away．”的说法，因为苹果性情温和，含有各种维生素和微量元素，是所有的水果中最接近完美的一个。\\n还有一种 说法：红色食品是相对于绿色食品而言的，指对人体有害的食品，如各种有毒有害、腐败变质、添加非食用物质的食品。红色食品危害人体健康乃至生命安全，对人体健康亮起了红灯，应当大力查处。"}, {"title": "作用", "content": "这些食品中富含β-胡萝卜素和维生素A，对孩子上皮组织和呼吸道粘膜有很强的保护作用，可提高预防感冒的能力。\\n假如你生来体质较弱，易受感冒病毒的困扰，或者已经被感冒缠上了，红色食品会助 你一臂之力，天生具有促进人体健康卫士之一的巨噬细胞活力的功能，巨噬细胞乃是感冒病毒等致病微生物的“杀手”，其活力增强了，感冒病毒自然难以在人体内立足，更谈不上生长繁殖了。至于颜色较辣椒稍浅一些的胡萝卜，所含的胡萝卜素可在体内转化为维生素A，发挥护卫人体上皮组织 如呼吸道黏膜的作用，常食之同样可以增强人体抗御感冒的能力。除了红辣椒、胡萝卜外，苋菜、洋葱、红枣、番茄、红薯、山楂、苹果、草莓、老南瓜、红米等亦具此功。"}, {"title": "红色食品与感冒", "content": "冬令时节，气候寒冷，万物收藏，人的机体生理功能处于降低、抑制、收缩状态，易患感冒，吃红色食品可扶正祛邪，增强免疫力，预防得病。[1]\\n蔬菜中的红萝卜、红辣椒、番茄、红薯、红枣、红苋菜等红色食品中，富含β-胡萝卜素，不但能清除人体氧自由基，而且参与合成维生素A，对人体上皮组织和 呼吸道黏膜有很强的保护作用。推荐以下几个食疗方—— —\\n★番茄猪肝汤\\n用料：猪肝250克，虾仁25克，蘑菇40克，鸡蛋1只，番茄150克，黄酒、葱段、姜片、胡椒粉、精盐适量。\\n制法：将猪肝切去筋膜洗净，切丁后加上酒、姜汁、蛋液、盐、胡椒粉，搅打成浆。用旺火蒸10—15分钟至结膏。清水加虾仁、黄酒沸煮5分钟后倒入蘑菇、番茄丁 和肝膏，再煮沸，调味即可。\\n功用：养肝明目，增强免疫力。用于防感冒、防治夜盲症及免疫力低下者，以及甲亢。\\n方解：猪肝有养肝明目、增强免疫力；蘑菇补益脾胃，益阴养肝，降压，降脂，润燥化痰，增加白细胞；虾仁、番茄均有增强免疫力的食品，番茄可增强营养，减少感冒的发生。\\n★红萝卜炖牛肉\\n用料：牛肉250克、红萝卜250克。\\n制法：牛肉切成小块，加黄酒、姜、葱等配料，再加入红萝卜块，炖熟，即可食用 。\\n功用：益气养胃、强健筋骨、增强免疫力。适用于防感冒及免疫力低、虚损消瘦、腰膝酸软者。\\n方解：牛肉补脾胃、益气血、强筋骨，红萝卜增强免疫力，防感冒，健脾，补血，助消化。\\n★蜂蜜红萝卜汁\\n用红萝卜汁与蜂蜜各半制成混合汁剂，每天饮用3次，每次1汤匙。可防治伤风、感冒和咽喉炎。胡萝卜能提供丰富的维生素A，具有促进机体正常生长与繁殖、维护上皮组织、防止感冒及保持视力正常。蜂蜜能补中，润燥，止 痛，解毒，清热。"}, {"title": "红色食品与红肉", "content": "红色食品是指外表呈红色的果蔬和“红肉”类。红色果蔬包括红辣椒、西红柿、红枣、山楂、草莓、苹果等，红色果蔬含有糖和多种维生素，尤其富含维生素C。“红肉”指牛肉、猪肉、羊肉及其制品。\\n红色果蔬中的辣椒具有温中散寒，开胃除湿之功效，辣椒中的辣椒素能刺激唾液和胃肠道消化液的分泌，还能刺激心血管系统，使心跳加快，血液循环加速，因此在寒冷环境有祛风除湿的作用。风寒型感冒病人食用辣椒汤能帮助发汗，有利于感冒的康复，但是胃肠疾病、结核病人则不适合食用。西红柿-在国外享有“ 金苹果”之称，具有较高的价值。由于西红柿含有94%左右的水分，生吃能防治中暑，止渴生津，凉血解毒的作用，但食西红柿时尽量少放盐，为了 避免维生素的破坏，做汤时最好等水开了再下西红柿，而且忌食未成熟的西红柿胃，胃肠虚寒者即慢性腹泻和消化不良者应忌食之。红枣在国外被称为“天然维生素丸”，具有很好的补血功效，能安神和补益脾胃，但胃肠积滞和患有牙齿疾病者应忌食。食用红枣时不宜与鱼同食，同食易引起腹部胀痛。\\n红色食品中的肉类即所谓“红肉”，主要含蛋白质和脂肪及其它无机盐等，因此具有丰富的营养价值。不过“红肉”致癌，世界癌症研究 基金会建议食用“红肉”时，每日每人撮入量应少于80克，这是因为“红肉”在烧烤、烙制、煎炸时，其表面产生多种杂环胺——致癌物。"}, {"title": "好处", "content": "红色不但能让人联想到爱情和激情，还是一种与心脏、大脑和泌尿系统的健康有关的颜色。红色的水果和蔬菜对我们的身体健康大有裨益。 红色的果蔬主要含有丰富的植物化学成分，包括抗细胞因子、抗氧化剂和番茄红素(一种产生红色的色素)。这些成分能够预防 癌症，特别是肺癌、前列腺癌和消化道癌。它们还可以延缓衰老，并且有利于防止黄斑变性。黄斑变性是导致65岁以上老年人失明的主要诱因。\\n1、草莓含有80%的水分、丰富的维生素C、少量膳食纤维和钾。由于含糖量很低，因此经常出现在减肥食谱中。大量抗坏血酸、凝集素和果胶使它成为降低血液中胆固醇含量的理想食物。传统医学中草莓可以作为润肤剂、净化剂和利胆剂，还具有镇咳和抗风湿的作用。人们还认为它有抗贫血和滋补的功效，可以促进机体生长。草莓叶子的浸剂还可以用于肠道消炎。\\n2、每天生食6至1 2颗樱桃对痛风和尿酸过多有显著疗效。樱桃的果汁有利于治疗腹泻和结肠炎，所含的抗氧化剂具有保健作用。樱桃含有的主要养分和膳食纤维较少，但是维生素B的含量不低。在矿物质中，钾和铁的含量较 高。\\n3、西瓜是水分含量最高的水果，高达其总重量的95%，因此可以促进肾脏更好地发挥功能，将废物和有毒物质排出体外。\\n4、覆盆子含有 丰富的维生素E、多种植物营养素和不可溶性纤维。除了具有利尿和通便作用，它还可以用于治疗风湿。\\n5、红苹果富含果胶、糖分和维生素C。此外，由于它是温和的通便剂，所以还具有特殊的医疗效用，可以用于治疗肠道功能紊乱。因此，自然医学认为红苹果可以抗腹泻、贫血和哮喘。它还能够缓解神经系统紧张，促进睡眠。每天晚上吃一个红苹果有助于迅速入睡。它还对希望保持体形的人有用，因为几乎不含脂肪，每100克只有不到58卡路里的热量。据法国图卢兹大学的研究结果显示，每天吃一个大苹果可以在8个星期内使胆固醇水平降低。\\n6、红辣椒中抗氧化剂、硒和维生素C的含量很高，甚至高于柑桔和柠檬等酸味水果。红辣椒所含的膳食纤维能够控制血液中的胆固醇和葡萄糖，还可以改善肠道功能。\\n7、红萝卜有 益于治疗呼吸系统疾病，例如咽炎和喉炎，还可以减轻喉咙嘶哑。在柠檬的辅助下，它还可以用来防治哮喘和鼻窦炎。萝卜酒具有清除肾结石和治疗肝脏和胆囊疾患的作用。红萝卜含有钾和少量铁，不含脂肪，每100克只含有15卡路里的热量。它非常适于制作凉拌沙拉，配上柠檬和盐就是一道佳 肴。此外，吃红萝卜还可以控制前列腺癌变。\\n8、番茄含有番茄红素和大量抗氧化剂，能够降低患上慢性疾病的危险，尤其是前列腺癌和心血管疾病。番茄具有提神、助消化和抗炎的作用。用它制作的沙拉、酱汁和菜泥可以帮助患有胃炎和胃溃疡的人更好地消化不易消化吸收的食物。番茄的热量很低，含有维生素C。它富含的番茄红素可以防止罹患前列腺癌。如果使用食用油烹调番茄，还可以增强这种功效。\\n"}], "tags": ["饮食", " 食品", "食疗", "科学", "健康", "食品类型"], "url": "http://baike.baidu.com/view/0010.htm"}\n'
```