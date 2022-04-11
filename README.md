﻿# **Python 大六壬 Kinliuren 堅大六壬 堅六壬**
[![Python](https://img.shields.io/pypi/pyversions/kinliuren)](https://pypi.org/project/kinliuren/)
[![PIP](https://img.shields.io/pypi/v/kinliuren)](https://pypi.org/project/kinliuren/)
[![Downloads](https://img.shields.io/pypi/dm/kinliuren)](https://pypi.org/project/kinliuren/)
[![TG](https://img.shields.io/badge/chat-on%20telegram-blue)](https://t.me/gnatnek)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?logo=paypal&style=flat-square)](https://www.paypal.me/kinyeah)&nbsp;

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/%E7%BA%8C%E4%BF%AE%E5%9B%9B%E5%BA%AB%E5%85%A8%E6%9B%B8%E7%AC%AC1057%E5%86%8A.pdf/page568-428px-%E7%BA%8C%E4%BF%AE%E5%9B%9B%E5%BA%AB%E5%85%A8%E6%9B%B8%E7%AC%AC1057%E5%86%8A.pdf.jpg "六壬軍帳神機")

## 1. 導讀 Introduction
大六壬，或稱六壬神課，簡稱六壬，是中國古老三大占卜術之一。大六壬與奇門遁甲、太乙神數並稱三式。大六壬盛行於漢朝、三國、魏晉南北朝，文人名士多有以此為休閒，常以懷中藏物互相占卜猜測，名曰「射覆」。唐宋以來，明清相繼，相承至今。然六壬演式繁雜，主要在士大夫之間流傳，在民間社會中漸被文王卦所代替。當今社會，在中國大陸、香港和台灣均有一部分人在研習六壬。六壬術傳至日本後，在平安時代由陰陽師安倍晴明發揚光大。為現代算命相術之一。

Da Liu Ren is a form of Chinese calendrical astrology dating from the later Warring States period. It is also a member of the Three Styles (三式; sānshì; 'three rites') of divination, along with Qi Men Dun Jia (奇门遁甲) and Taiyi (太乙).

In the words of a contemporary Chinese master of Da Liu Ren, the six rén indicate an entire movement of the sexagenary cycle, during which an something may appear, rise to maturity and then decline and disappear. Thus the six rén indicate the life cycle of phenomena. There is a homonym in the Chinese language which carries the meaning of pregnancy and so the six rén also carry the meaning of the birth of a phenomenon.

## 2. 安裝套件 Installation
```python
	pip install kinliuren
```
## 3. 起課方式 Quickstart
```python
	from kinliuren import kinliuren
	kinliuren.Liuren( 節氣, 農曆月份, 日干支, 時干支).result(0)
	例如 Liuren("驚蟄","二","己未","甲午").result(0)
{'節氣': '驚蟄', '日期': '己未日甲午時', '格局': ['賊尅', '重審'], '日馬': '巳', '三傳': {'初傳': ['巳', '虎', '父', '丁'], '中傳': ['戌', '雀', '兄', '壬'], '末傳': ['卯', '玄', '官', '乙']}, '四課': {'四課': ['巳子', '虎'], '三課': ['子未', '貴'], '二課': ['巳子', '虎'], '一課': ['子己', '貴']}, '天地盤': {'天盤': ['亥', '子', '丑', '寅', '卯', '辰', '巳', '午', '未', '申', '酉', '戌'], '地盤': ['午', '未', '申', '酉', '戌', '亥', '子', '丑', '寅', '卯', '辰', '巳'], '天將': ['蛇', '貴', '后', '陰', '玄', '常', '虎', '空', '龍', '勾', '合', '雀']}, '地轉天盤': {'午': '亥', '未': '子', '申': '丑', '酉': '寅', '戌': '卯', '亥': '辰', '子': '巳', '丑': '午', '寅': '未', '卯': '申', '辰': '酉', '巳': '戌'}, '地轉天將': {'午': '蛇', '未': '貴', '申': '后', '酉': '陰', '戌': '玄', '亥': '常', '子': '虎', '丑': '空', '寅': '龍', '卯': '勾', '辰': '合', '巳': '雀'}, '神煞': {'天城': '申', '天吏': '寅', '皇書': '寅', '天喜': '戌', '天耳': '申', '戲神': '巳', '遊神': '丑', '天車': '巳', '月馬': '辰', '日馬': '巳', '丁馬': '巳', '日德': '寅', '日祿': '午', '賢貴': '丑', '進神': '卯', '進神二': '酉', '五合': '寅', '支德': '午', '將星': '卯', '六合': '午', '天馬': '申', '聖心': '巳', '天恩': '酉', '天財': '午', '飛廉': '巳', '會神': '戌', '成神': '申', '生氣': '丑', '月合': '戌', '閃電': '丑'}}
```
## 4. 六壬古籍

| 年份          | 作者           | 書名                                            | 備註       |
| ------------- | ------------- | --------------------------------------------- | ------------- |
| 晉  | 郭璞  | 大六壬五變中黃經 | |
| 晉  | 郭璞  | 大六壬九天中黃經三卷 | 清鈔本 |
| 唐  | 呂才  | 六壬軌限照心神鑑經三卷 | |
| 宋  | 徐道符  | 大六壬心鏡八卷 | 實事求是齋鈔本（存卷一至七） |
| 宋  | 劉啓明  | 六壬軍帳賦一卷 | |
| 宋  | 楊維德  | 景祐六壬神定經二卷 | |
| 宋  | 祝泌 | 六壬大占一卷 | |
| 金  | 徐次賓 | 大六壬一字訣玉連環一卷 | |
| 明  | 適適子 | 大六壬神課金口訣六卷別錄一卷 | |
| 明  | 徐陰 | 雲南劉雨府六壬心鏡集注三卷 | |
| 明  | 佚名 | 大六壬通天銀河棹八卷 | |
| 明  | 佚名 | 大六壬搜原真訣銀河棹不分卷 | |
| 明  | 劉基 | 大六壬銀河棹不分卷 | |
| 明  | 張松源 | 銀河棹 | |
| 明  | 佚名  | 六壬行軍指南不分卷 | |
| 明  | 佚名  | 占候六壬遁法不分卷 | |
| 明  | 陳公獻  | 大六壬五變中黃經正文一卷釋義四卷 | |
| 明  | 陳公獻  | 大六壬苗公射覆鬼撮腳 | |
| 明  | 佚名  | 六壬兵法書不分卷 |  |
| 明  | 佚名  | 六壬決勝兵機不分卷 |  |
| 明  | 佚名  | 六壬兵帳不分卷 |  |
| 明  | 陳應選  | 大六壬兵機確論出師全書不分卷 | 明崇禎二年木活字印朱墨套印本  |
| 明  | 佚名  | 六壬兵機不分卷 |  |
| 明  | 朱恆  | 大六壬會要全集十二卷 | 清經鉏堂鈔本 |
| 明  | 佚名  | 大六壬翠羽歌三卷 | 明嘉靖三十七年高大器鈔本 |
| 明  | 官應震 | 六壬統宗十卷 |  |
| 明  | 官應震 | 六壬成式 |  |
| 明  | 官應震 | 大六壬雜釋八卷 |  |
| 明  | 官應震 | 大六壬管見全書十二卷 |  |
| 明  | 佚名  | 大六壬金櫃經一卷 |  |
| 明  | 佚名  | 新編詳註大六壬斷經祕訣十卷課起例口訣一卷 |  |
| 明  | 佚名  | 六壬課經集四卷 |  |
| 明  | 佚名  | 六壬兵占一卷 |  |
| 明  | 佚名  | 六壬三黔集覽不分卷 |  |
| 明  | 佚名  | 新訂六壬總要不分卷 |  |
| 明  | 佚名  | 六壬集要四卷 |  |
| 明  | 佚名  | 六壬分野一卷 |  |
| 明  | 佚名  | 六壬龜甲統宗不分卷 |  |
| 明  | 佚名  | 六壬鈐說釋義不分卷 |  |
| 明  | 佚名  | 大六壬彙纂十二卷 |  |
| 明  | 榮陽子 | 大六壬叢書 | 明末藍格鈔本 |
| 明  | 佚名 | 彙纂大六壬玉鑰匙心訣 | 明清間鈔本 |
| 明  | 佚名  | 六壬集應鈐不分卷 |  |
| 明  | 佚名  | 六壬日占不分卷 |  |
| 明  | 佚名  | 六壬雲開觀月經一卷 | 始豐山房鈔本 |
| 明  | 佚名  | 大六壬大全十二卷 | 文淵閣四庫全書本 |
| 明  | 佚名  | 太上六壬明鑑符陰經四卷 | 道藏本（正統刻） |
| 明  | 黃賓廷  | 大六壬集應鈐六十卷首一卷 |  |
| 清  | 程樹勳  | 精鈔歷代六壬占驗匯選 |  |
| 清  | 佚名  | 六壬正易軍帳勾玄鈐 |  |
| 清  | 佚名  | 六壬軍帳神機六十卷 | 清藍格鈔本 |
| 清  | 佚名  | 六壬軍帳賦一卷 | 〖明〗王鳴鶴著 |
| 清  | 佚名  | 六壬九種 |  |
| 清  | 程起鸞、陳良謨  | 大六壬指南五卷 | 順治九年刻 |
| 清  | 郭載騋 | 大六壬大全十三卷 | 清康熙四十三年刻本 |
| 清  | 巫國匡 | 訂正六壬金口訣四卷 |  |
| 清  | 毛志道 | 六壬經緯六卷 |  清雍正二年山淵堂刻本 |
| 清  | 張鳳藻 | 儀度六壬選日要訣三卷 |  |
| 清  | 紀大奎 | 六壬類聚四卷 | 紀慎齋先牛全集本（嘉慶刻、同治刻） |
| 清  | 張純照 | 大六壬尋原 | 清嘉慶二十三年樂淳堂張氏刻本 |
| 清  | 佚名| 六壬精蘊 | 清嘉慶間鈔本 |
| 清  | 劉赤江 | 六壬粹言六卷首一卷 | 清道光六年知止齋刻本 |
| 清  | 張官德 | 六壬辨疑四卷 | 清同治八年源堂刻本 |
| 清  | 佚名 | 大六壬口華百章歌一卷 | 清同治間梁承誥鈔本 |
| 清  | 佚名 | 大六壬占例不分卷 | 清同治十二年梁承誥鈔本 |
| 清  | 李沺 | 六壬摘要六卷附罪言一卷 | 游藝錄本（光緒刻） |
| 清  | 佚名 | 六壬全課占斷集成 | 清光緒間鈔本 |
| 清  | 苗公達 | 大六壬斷章祕訣一卷 | 實事求是齋鈔本 |
| 清  | 葉悔亭 | 六壬眎斯四卷 |  |
| 清  | 錢耕畸 | 六壬精蘊二十卷 | 鈔本（清李培南藏） |
| 清  | 知空子 | 六壬捷步不分卷 |  |
| 清  | 李雲龍 | 大六壬合纂八卷 |  |
| 清  | 佚名  | 大六壬類占二卷 | 清同治十二年梁承誥鈔本 |
| 清  | 佚名  | 大六壬占身命摘要一卷 | 清同治年梁承誥鈔本 |
| 清  | 佚名 | 六壬聚玉集不分卷 |  清乾隆間鈔本 |
| 清  | 佚名 | 黃帝大六壬鬼撮腳 |  |
| 清  | 佚名 | 大六壬淵鑑不分卷 |  |
| 清  | 佚名 | 大六壬正義口訣斷章不分卷 |  |
| 清  | 佚名 | 大六壬會通摘要不分卷 |  |
| 清  | 佚名 | 大六壬神煞全圖 |  |
| 清  | 佚名 | 六壬彙鈐十二卷 |  |
| 清  | 佚名 | 六壬盤式一卷 |  |
| 清  | 佚名 | 大六壬會通摘要不分卷 |  |
| 清  | 佚名 | 六壬課義二卷 |  |
| 清  | 佚名 | 六壬課式一卷 |  |
| 清  | 佚名 | 六壬雜輯 |  |
| 清  | 佚名 | 六壬統畧 |  |
| 清  | 佚名 | 大六壬課鈐一卷 |  |
| 清  | 佚名 | 六壬類纂神課 |  |
| 清  | 佚名 | 六壬占斷書 |  |
| 清  | 佚名 | 大六壬課傳集解十二卷 |  |
| 清  | 程樹勛 | 壬學瑣記一卷 |  |
| 清  | 佚名 | 六壬軌跡照心經不分卷 |  |
| 清  | 佚名 | 六壬金璧二卷 |  |
| 清  | 佚名 | 六壬掌鏡不分卷 |  |
| 清  | 佚名 | 大六壬準繩一卷 |  |
| 清  | 佚名 | 六壬精要不分卷 |  |
| 清  | 佚名 | 六壬祕占不分卷 |  |
| 清  | 佚名 | 六壬說約不分卷 |  |
| 清  | 佚名 | 大六壬袖傳捷要一卷 |  |
| 清  | 佚名 | 六壬獨悟絕法不分卷 |  |
| 清  | 佚名 | 大六壬隔山照不分卷 |  |
| 清  | 佚名 | 六壬鬼料竅不分卷 |  |
| 清  | 佚名 | 六壬初學便覽不分卷 |  |
| 清  | 佚名 | 邵彥和先生六壬斷案分編不分卷 |  |
| 清  | 佚名 | 六壬總論 |  |
| 清  | 佚名 | 六壬集鈐不分卷 |  |
| 清  | 佚名 | 六壬通仙四卷 |  |
| 清  | 愈樾 | 遊藝錄六卷 | 載於春在堂全書。  |
| 清  | 劉克猷 | 六壬捷錄 |  |
| 清  | 高修纂 | 大六壬明體經 |  |
| 清  | 雲湖樂道人 | 大六壬神妙要書六卷 | 清末民國初鈔本 |
| 清  | 佚名 | 太乙六壬雷公運式遁甲通神經一卷 |  |
| 清  | 楊克讓 | 六壬鉗斷一卷 |  |
| 清  | 張廷楨 | 嚴陵張九儀儀度六壬選日要訣不分卷 | 清末刻本 |
| 清  | 佚名 | 大六壬未語書 | 清末刻本 |
| 現代  | 吳師青  | 大六壬靈覺經四卷 |  |

