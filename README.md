# WZRYKPLdata：
This is a program aiming for study. Every earnt in it will be donate
##################################################################
                      Annoncement
This Program is the homework of the Individual Assignment 1: Digital Solopreneurship Lean Startup Business Plan of MKTG 6041M e-platform Entrepreneurship， belongs to Ivan ZHOU

The core codes are writen through vibe coding, by the glm-4.7 ai agent from big model.
################################################################## 
                           Introduction
The raw data of WZRY matches is in the :WZRY_修正_20260211_112715.xlsx
The Html code is in the index.html
The 收款码.jpg was the paying method to validate this MVP

###################################################################
              Prompt for vibe coding
你是一个高级产品架构师 + 数据系统设计专家。我正在做一个基于WZRY职业赛事数据的可访问网站。数据来源只有一张 Excel 表
你需要利用Html和Javascripts构建一个三层结构的赛事数据分析网站：
1️⃣ 主队数据层
2️⃣ 对战数据层
3️⃣ 赛事大数据层
📌 第一部分：主队数据层
用户选择一支职业战队作为“主队”。请设计该页面完整结构，包括：
1.1 主队基本信息：总比赛场次；总胜率；红色方场次 & 胜率；蓝色方场次 & 胜率；最喜爱对手（近5场交手胜率最高Top3）；最害怕对手（近5场交手胜率最低Top3）
1.2 主队BP分析层：场次；胜率；Ban率最高英雄 Top5；Pick率最高英雄 Top5；胜率最高英雄（使用≥5场）；最爱组合（2英雄组合、3英雄组合）；红色方爱ban英雄；红色方爱选英雄；蓝色方爱ban英雄；蓝色方爱选英雄；红色方前两个Pick最常见英雄；蓝色方第一Pick最常见英雄；蓝色方最怕英雄（遇到≥5场且胜率最低Top5）；红色方最怕英雄（遇到≥5场且胜率最低Top5）
📌 第二部分：对战数据层：用户选择另一支战队作为对手。
2.1 对方战队基本信息：同主队结构。
2.2 对方BP思路分析：结构与主队一致，但必须限定在：“与主队交手的比赛数据”
📌 第三部分：赛事大数据层：基于全量比赛。
3.1 全局红蓝方数据：红方总场次 & 胜率；蓝方总场次 & 胜率
3.2 全局BP信息：结构与战队BP一致，但基于全部比赛。
3.3 英雄数据层；胜率最高英雄（≥5场）；胜率最低英雄（≥5场）；使用率最高装备Top5
选择某英雄后展示：胜率最高装备；出场率最高装备；出装路径频率排行

This is the Translation of prompt
You are a senior product architect and data system design expert. I'm building an accessible website based on WZRY professional esports data. The data source is only one Excel spreadsheet.
You need to build a three-tiered esports data analysis website using HTML and Javascript:
1️⃣ Home Team Data Layer
2️⃣ Match Data Layer
3️⃣ Big Esports Data Layer
📌 Part 1: Home Team Data Layer Users select a professional esports team as their "home team". Please design the complete structure of this page, including:
1.1 Home Team Basic Information: Total number of matches; Total win rate; Number of matches & win rate for the red team; Number of matches & win rate for the blue team; Favorite opponents (Top 3 with the highest win rate in the last 5 encounters); Most feared opponents (Top 3 with the lowest win rate in the last 5 encounters)
1.2 Home Team BP Analysis Layer: Number of matches; Win rate; Top 5 heroes with the highest ban rate; Top 5 heroes with the highest pick rate; Heroes with the highest win rate (used ≥5 times); Favorite combinations (2-hero combinations, 3-hero combinations); Heroes the red team likes to ban; Heroes the red team likes to pick; Heroes the blue team likes to ban; Heroes the blue team likes to pick; Most common heroes picked by the red team in their first two picks; Most common hero picked by the blue team in their first pick; Heroes the blue team fears most (Top 5 with the lowest win rate after ≥5 encounters); Heroes the red team fears most (Top 5 with the lowest win rate after ≥5 encounters)
📌 Part Two: Match Data Layer: The user selects another team as their opponent.
2.1 Opponent Team Basic Information: Same structure as the home team.
2.2 Opponent's BP Strategy Analysis: Structure is the same as the home team, but must be limited to: "Match data against the home team".
📌 Part Three: Tournament Big Data Layer: Based on all matches.
3.1 Global Red/Blue Team Data: Red Team Total Matches & Win Rate; Blue Team Total Matches & Win Rate
3.2 Global BP Information: Structure is the same as the team's BP, but based on all matches.
3.3 Hero Data Layer: Heroes with the highest win rate (≥5 matches); Heroes with the lowest win rate (≥5 matches); Top 5 most used items. After selecting a hero, the following will be displayed: Most used items; Most frequently used items; Item build frequency ranking.
