🤩Touhou character conversation dataset🤩
=============

<img src="/Images/Touhou_logo.png" width="600px" height="300px" title="Touhou Project Logo" alt="Touhou Project Logo"></img><br/>

I am glad to present this dataset to you. 
With this, we could fine-tune the basic knowledge of Touhou Project.
There are total 1300+ QA with 101 available characters and 21 primary characters.

What's the differnce of primary and available characters?
-------

Primary characters are made up of 20 characters 
that are in Top 20 in Touhou wiki popularity vote + Yakumo Ran
Primary characters has 20 (special qestions) + 9(universal questions)
but available characters except for primary has only 9 universal QA.

This is the list of primary characters:
-------------

|id|name|
|---|---|
|id:0|Alice Margatroid|
|id:1|Aya Shameimaru|
|id:2|Cirno|
|id:3|Flandre Scarlet|
|id:4|Fujiwara no Mokou|
|id:5|Koishi Komeiji|
|id:6|Marisa Kirisame|
|id:7|Patchouli Knowledge|
|id:8|Ran Yakumo|
|id:9|Reimu Hakurei|
|id:10|Reisen Udongein Inaba|
|id:11|Remilia Scarlet|
|id:12|Rumia|
|id:13|Sakuya Izayoi|
|id:14|Sanae Kochiya|
|id:15|Satori Komeiji|
|id:16|Suwako Moriya|
|id:17|Tenshi Hinanai|
|id:18|Youmu Konpaku|
|id:19|Yukari Yakumo|
|id:20|Yuyuko Saigyouzi|

This is list of available characters except for primary characters:
-------------

|id|name|
|---|---|
|id:0|Byakuren Hijiri|
|id:1|Chen|
|id:2|Clownpiece|
|id:3|Daiyousei|
|id:4|Doremy Sweet|
|id:5|Eirin Yagokoro|
|id:6|Futatsuiwa Mamizo|
|id:7|Hata no Kokoro|
|id:8|Hecatia Lapislazuli|
|id:9|Hieda no Akyuu|
|id:10|Himekaidou Hatate|
|id:11|Hina Kagiyama|
|id:12|Hong Meiling|
|id:13|Ichirin Kumoi|
|id:14|Iku Nagae|
|id:15|Junko|
|id:16|Kagerou Imaizumi|
|id:17|Kaguya Houraisan|
|id:18|Kaku Seiga|
|id:19|Kanako Yasaka|
|id:20|Kasen Ibaraki|
|id:21|Keiki Haniyasushin|
|id:22|Keine Kamishirasawa|
|id:23|Kisin Sagume|
|id:24|Koakuma|
|id:25|Komachi Onozuka|
|id:26|Komano Aunn|
|id:27|Kyouko Kasodani|
|id:28|Letty Whiterock|
|id:29|Lily White|
|id:30|Luna Child|
|id:31|Lunasa Prismriver|
|id:32|Lyrica Prismriver|
|id:33|Medicine Melancholy|
|id:34|Merlin Prismriver|
|id:35|Mima|
|id:36|Minamitsu Murasa|
|id:37|Minoriko Aki|
|id:38|Miyako Yoshika|
|id:39|Momiji Inubashiri|
|id:40|Mononobe no Futo|
|id:41|Mystia Lorelei|
|id:42|Nazrin|
|id:43|Nishida Satono|
|id:44|Nitori Kawashiro|
|id:45|Niwatari Kutaka|
|id:46|Nue Houjuu|
|id:47|Okina Matara|
|id:48|Parsee Mizuhashi|
|id:49|Raiko Horikawa|
|id:50|Rin Kaenbyou|
|id:51|Ringo|
|id:52|Rinnosuke Morichika|
|id:53|Sariel|
|id:54|Seija Kijin|
|id:55|Seiran|
|id:56|Sekibanki|
|id:57|Shikieiki Yamaxanadu|
|id:58|Shinki|
|id:59|Shinmyoumaru Sukuna|
|id:60|Shizuha Aki|
|id:61|Shou Toramaru|
|id:62|Soga no Tojiko|
|id:63|Star Sapphire|
|id:64|Suika Ibuki|
|id:65|Sunny Milk|
|id:66|Tatara Kogasa|
|id:67|Teireida Mai|
|id:68|Tewi Inaba|
|id:69|Toyosatomimi no Miko|
|id:70|Usami Sumireko|
|id:71|Utsuho Reiuji|
|id:72|Wakasagihime|
|id:73|Watatsuki no Toyohime|
|id:74|Watatsuki no Yorihime|
|id:75|Wriggle Nightbug|
|id:76|Yorigami Joon|
|id:77|Yorigami Shion|
|id:78|Yuka Kazami|
|id:79|Yumemi Okazaki|
|id:80|Yuugi Hoshiguma|

Example of QA:
-------------

```
Q:오늘 날씨가 흐린 것 같지 않아요?

A(Fujjiwara no Mokou):그렇네요. 하늘에 구름이 많아요. 하지만, 날씨는 내 영생에 별 영향을 주지 않아요. 뭐, 이 흐린 날이 불멸의 삶의 우울함에 어울리는 건 인정하죠. 당신은 날씨가 중요한 편인가요?
```


Limitations:
-------------

* There's only 29 qustions in 1300+ QA.
> 1. That's because Touhou has so many characters.
* It's all generated by GPT-4.5 turbo
> 1. Unique place names or character names like Gensokyo, Scarlet Devil Mansion
are almost all replaced to right Korean translation.
> 2. Some of mentions that contains not correct Touhou information has been replaced to right answer


When you are using Touhou dataset:
----------

```
### Please credit the source
Thank you
```
  

