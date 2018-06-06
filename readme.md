# 数据使用

1. alluserlocal相关的两个文件是收集到的20万左右用户的相关信息，字段如下：

   | 字段       | 含义                   |
   | :--------- | ---------------------- |
   | vipDueDate | 大会员结束时间戳       |
   | vipStatus  | 是否大会员             |
   | vipType    | 是否年费大会员         |
   | likevideo  | 喜欢的番剧对应的id列表 |

   

2. bilibili是在2018年4月左右的所有番剧的名称和基本信息，specific_final是对应的详情信息，用animeId进行1对1关系的建立。

   bilibili：

   | 字段            | 含义     |
   | :-------------- | -------- |
   | animePictureUrl | 番剧图   |
   | animeFinished   | 是否完结 |
   | animeId         | 主键     |
   | fans            | 粉丝数   |
   | animeTitle      | 番剧名称 |

   

   specific

   | 字段        | 含义                 |
   | ----------- | -------------------- |
   | score       | 评分                 |
   | count       | 评分人数             |
   | tags        | 标签                 |
   | animeId     | 与bilibili对应的主键 |
   | evaluate    | 简介                 |
   | coins       | 硬币量               |
   | actor       | 出演的声优           |
   | episodes    | 每集相关数据         |
   | index       | 集数                 |
   | update_time | 上传时间(string)     |
   | index_title | 单集名               |
   | coins       | 单集硬币数           |
   | ...         | ...(too many)        |



