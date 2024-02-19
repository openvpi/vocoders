# DiffSinger Community Vocoder Project

## Copy Synthesis Demo

**Ground Truth:**

<audio controls><source src="wavs/gt_00.wav" type="audio/wav"></audio>

**Prediction:**

<audio controls><source src="wavs/pred_00.wav" type="audio/wav"></audio>

## Acknowledgements

Training data of the vocoders is provided and used under permissions by the following organizations, societies or individuals:

|   Signature    |                             Link                             |
| :------------: | :----------------------------------------------------------: |
|      孙飒      |        [https://www.qfssr.cn](https://www.qfssr.cn/)         |
| 赤松_Akamatsu  |      [https://www.zhibin.club](https://www.zhibin.club)      |
|      乐威      |      [https://www.zhibin.club](https://www.zhibin.club)      |
|      伯添      | [https://space.bilibili.com/24087011](https://space.bilibili.com/24087011) |
|     雲宇光     | [https://space.bilibili.com/660675050](https://space.bilibili.com/660675050) |
|     橙子言     | [https://space.bilibili.com/318486464](https://space.bilibili.com/318486464) |
|    人衣大人    | [https://space.bilibili.com/2270344](https://space.bilibili.com/2270344) |
|      玖蝶      | [https://space.bilibili.com/676771003](https://space.bilibili.com/676771003) |
|     Yuuko      |                                                              |
|   白夜零BYL    | [https://space.bilibili.com/1605040503](https://space.bilibili.com/1605040503) |
|      嗷天      | [https://space.bilibili.com/5675252](https://space.bilibili.com/5675252) |
|     洛泠羽     | [https://space.bilibili.com/347373318](https://space.bilibili.com/347373318) |
| 灰条纹的灰猫君 | [https://space.bilibili.com/2083633](https://space.bilibili.com/2083633) |
|      幽寂      | [https://space.bilibili.com/478860](https://space.bilibili.com/478860) |
|    恶魔王女    | [https://space.bilibili.com/2475098](https://space.bilibili.com/2475098) |
|      芮晴      |                                                              |
|      绮萱      | [https://y.qq.com/n/ryqq/singer/003HjD6H4aZn1K](https://y.qq.com/n/ryqq/singer/003HjD6H4aZn1K) |
|      诗芸      | [https://y.qq.com/n/ryqq/singer/0005NInj142zm0](https://y.qq.com/n/ryqq/singer/0005NInj142zm0) |
|      汐蕾      | [https://y.qq.com/n/ryqq/singer/0023cWMH1Bq1PJ](https://y.qq.com/n/ryqq/singer/0023cWMH1Bq1PJ) |
|   1262917464   |                                                              |
|      炜阳      |                                                              |
|   叶卡yolka    |                                                              |
|     幸の夏     | [https://space.bilibili.com/1017297686](https://space.bilibili.com/1017297686) |
|    暮色未量    | [https://space.bilibili.com/272904686](https://space.bilibili.com/272904686) |
|    晓寞sama    | [https://space.bilibili.com/3463394](https://space.bilibili.com/3463394) |
| 没头绪的节操君 |                                                              |
|    串串BunC    | [https://space.bilibili.com/95817834](https://space.bilibili.com/95817834) |
|      落雨      | [https://space.bilibili.com/1292427](https://space.bilibili.com/1292427) |
|  长尾巴的翎艾  | [https://space.bilibili.com/1638666](https://space.bilibili.com/1638666) |
|    声闻计划    | [https://space.bilibili.com/392812269](https://space.bilibili.com/392812269) |
|   唐家大小姐   | [http://5sing.kugou.com/palmusic/default.html](http://5sing.kugou.com/palmusic/default.html) |
|     不伊子     |                                                              |
|     芸青岩     | [https://space.bilibili.com/35236775](https://space.bilibili.com/35236775) |
|      妖橙      | [https://space.bilibili.com/161975631](https://space.bilibili.com/161975631) |
|      双桨      | [https://space.bilibili.com/13245483](https://space.bilibili.com/13245483) |
|      灵滅      | [https://space.bilibili.com/276988145](https://space.bilibili.com/276988145) |
|    AlexYHX     | [https://space.bilibili.com/13303439](https://space.bilibili.com/13303439) |
|      祁唱      | [https://space.bilibili.com/11256670](https://space.bilibili.com/11256670) |
|     早稻叽     | [https://space.bilibili.com/1950658](https://space.bilibili.com/1950658) |

The following public datasets are used:

|       Dataset       |                             Link                             |
| :-----------------: | :----------------------------------------------------------: |
|      Opencpop       | [https://wenet.org.cn/opencpop/](https://wenet.org.cn/opencpop/) |
|       CCMUSIC       | [https://ccmusic-database.github.io/index.html](https://ccmusic-database.github.io/index.html) |
| SingingVoiceDataset | [http://isophonics.net/SingingVoiceDataset](http://isophonics.net/SingingVoiceDataset) |

## License

The model weights are licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Anyone who distributes the model weights should include a copy of the license, a notice informing that the models are provided by the **OpenVPI Community** (or **DiffSinger Community**), and a link referring [this page](https://openvpi.github.io/vocoders/) (or a complete contribution list).

## Downloads

|    model    |    date    |                        specifications                        |            dataset             | iters |                             link                             |
| :---------: | :--------: | :----------------------------------------------------------: | :----------------------------: | :---: | :----------------------------------------------------------: |
| NSF-HiFiGAN | 2022-12-11 | 44.1 kHz sampling rate, hop size 512, 128 mel bins, input frequency 40-16000 |          ~93h singing          | >= 1M | [link](https://github.com/openvpi/vocoders/releases/tag/nsf-hifigan-v1) |
| NSF-HiFiGAN | 2024-02-19 | 44.1 kHz sampling rate, hop size 512, 128 mel bins, input frequency 40-16000 | ~72h singing (for fine-tuning) | 110K  | [link](https://github.com/openvpi/vocoders/releases/tag/nsf-hifigan-44.1k-hop512-128bin-2024.02) |

