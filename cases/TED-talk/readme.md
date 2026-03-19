## TED 演讲数据
- [TED talks](https://github.com/Chando0185/Multiverse_of_100-_data_science_project_series/tree/main/TED%20Talk)
  - 记录 4467 条 TED 演讲的相关信息。
  - 共三份数据 (约 15 MB, 2006-2020)：
    - `tags_dataset.csv`：包含了每场演讲的标签信息，每条数据包含 `ID` 和 `标签` 两个变量。同一个 ID 下有 5-7 个 Tags
    - `tedx_dataset.csv`：包含了每场演讲的相关信息，记录了 4467 条数据，每条数据包含 `ID`、`演讲者`、`标题`、`详情`、`发布时间`、`URL`、`观看次数` 七个变量。
    - `watch_next_dataset.csv`：用户观看的下一个 TED 演讲的 URL 和 ID。


## 用途

- 词云分析、标签分析、推荐系统等。
- 练习文本分析和自然语言处理（NLP）技能。
- 分析 TED 演讲的主题、标签和观看趋势，探索不同类型演讲的受欢迎程度。
- 通过分析用户观看的下一个 TED 演讲，了解用户的兴趣和行为模式。

## 数据概览

### tags_dataset.csv

```csv
idx,tag
8d2005ec35280deb6a438dc87b225f89,TED
8d2005ec35280deb6a438dc87b225f89,talks
8d2005ec35280deb6a438dc87b225f89,design
8d2005ec35280deb6a438dc87b225f89,society
8d2005ec35280deb6a438dc87b225f89,identity
8d2005ec35280deb6a438dc87b225f89,social change
8d2005ec35280deb6a438dc87b225f89,community
8d2005ec35280deb6a438dc87b225f89,humanity
8d2005ec35280deb6a438dc87b225f89,TEDx
94ded6639b0277d8f48ccaf5991417c3,TED
94ded6639b0277d8f48ccaf5991417c3,talks
94ded6639b0277d8f48ccaf5991417c3,alternative energy
94ded6639b0277d8f48ccaf5991417c3,cars
94ded6639b0277d8f48ccaf5991417c3,climate change
94ded6639b0277d8f48ccaf5991417c3,culture
94ded6639b0277d8f48ccaf5991417c3,environment
94ded6639b0277d8f48ccaf5991417c3,global issues
94ded6639b0277d8f48ccaf5991417c3,science
94ded6639b0277d8f48ccaf5991417c3,sustainability
94ded6639b0277d8f48ccaf5991417c3,technology

```

### tedx_dataset.csv

```csv
idx,speaker,title,description,date,url,views
8d2005ec35280deb6a438dc87b225f89,Alexandra Auer,The intangible effects of walls,…….,Posted Apr 2020,https://www.ted.com/talks/alexandra_auer_the_intangible_effects_of_walls_apr_2020,
94ded6639b0277d8f48ccaf5991417c3,Al Gore,…….,Posted Jun 2006,https://www.ted.com/talks/al_gore_averting_the_climate_crisis,
```

### watch_next_dataset.csv

```csv

```