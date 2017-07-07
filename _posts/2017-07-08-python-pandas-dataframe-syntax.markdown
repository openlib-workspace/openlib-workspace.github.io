---
title: Python Pandas DataFrame 사용법 정리
layout: post
---
자주 사용하는 DataFrame의 문법을 정리합니다.

# DataFrame을 한 행씩 가져오는 방법

{% highlight python %}
for index, row in df:
    print(index)
    print(row)
{% endhighlight %}
