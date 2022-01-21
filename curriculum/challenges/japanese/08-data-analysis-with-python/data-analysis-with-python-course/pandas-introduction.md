---
id: 5e9a093a74c4063ca6f7c158
title: Pandas 入門
challengeType: 11
videoId: 0xACW-8cZU0
bilibiliIds:
  aid: 975510116
  bvid: BV1u44y1b7fD
  cid: 409013433
dashedName: pandas-introduction
---

# --description--

*動画で説明しているように、notebooks.ai を使用する代わりに Google Colab を使用することができます。*

その他のリソース:

-   [GitHub のノート](https://github.com/ine-rmotr-curriculum/freecodecamp-intro-to-pandas)
-   [Google Colab を使用して GitHub からノートを開く方法](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

# --question--

## --text--

次のコードは何を表示しますか？

```py
import pandas as pd

certificates_earned = pd.Series(
    [8, 2, 5, 6],
    index=['Tom', 'Kris', 'Ahmad', 'Beau']
)

print(certificates_earned)
```

## --answers--

```
Tom      8
Kris     2
Ahmad    5
Beau     6
dtype: int64
```

---

```
Kris     2
Ahmad    5
Beau     6
Tom      8
dtype: int64
```

---

```
Tom      8
Kris     2
Ahmad    5
Beau     6
Name: certificates_earned dtype: int64
```

## --video-solution--

1
