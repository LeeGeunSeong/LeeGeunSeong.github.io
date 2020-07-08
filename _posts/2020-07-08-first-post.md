---
layout: post
title: 마크다운 정리~
# image: /img/hello_world.jpeg
gh-repo: LeeGeunSeong/leegeunseong.github.io
gh-badge: [star, fork, follow]
comments: true
---

제목(Header)
-----
```md
# h1
## h2
### h3
#### h4
##### h5
###### h6

h1
====

h2
----
```
강조(Emphasis)
----
```md
<em> _em_
<strong> __strong__
<del> ~~del~~
<u> `u`
```

목록(List)
----

```md
1. ordered list
2. ordered list
   - unordered list
   - unordered list
3. ordered list
   1. ordered list
   2. ordered list
4. ordered list

- ul에 사용 가능한 기호
   -, *, +
```

1. ordered list
2. ordered list
   - unordered list
   - unordered list
3. ordered list
   1. ordered list
   2. ordered list
4. ordered list

링크(Links)
----

```md
[Link Name](Link address)

[relative link](../img/avatar-icon.png)

https://google.com
<https://google.com>

```

[Link Name](Link address)

[relative link](../img/avatar-icon.png)

https://google.com

<https://google.com>

이미지(Image)
----
```md
![alt text](img address)
![alt][img]

[img]: http://~~~~

[![img link](~~.png)](link address) // 이미지 링크
```

코드 강조
----

```md
`code 강조`

```code종류

```　

```

표(Table)
----

```md
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |
```

| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |

인용문(quote)
----

```md
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3
```

인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3

수평선 `---` `***` `___`
----

줄바꿈 `<br>` `space 2번`
----

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
