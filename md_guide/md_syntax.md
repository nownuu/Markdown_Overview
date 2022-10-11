## 마크다운(markdown, md)의 문법


### 1. 제목(Header)
제목의 문법은 #부터 ######까지 #의 개수(1~6)로 크기를 조절하여 사용 가능하다.

```markdown
# 제목
## 제목
### 제목
#### 제목
##### 제목
###### 제목
```

-------

### 2. 구분선(Division Line)
구분선의 문법은 하이픈(-)과 별표(*)를 사용 가능하며 3개 이상 작성해야한다.
```markdown
---
- - -
-------

***
* * *
*********
```

------

### 3. 불릿(Bullet)
불릿은 +, *, - 모두 사용 가능하다. 들여쓰기가 가능하며 들여쓰기가 되는 경우 흰색의 불릿으로 표기가 된다.
```markdown
+
    +
    +

*  
    *
    *

-
    -
    -
```
-------

### 4. 인덱싱(Indexing)
인덱신은 순서를 매길 때 사용한다. 들여쓰기가 불가능하다.
```markdown
1.
2.
3.
```

------

### 5. 텍스트 강조(Emphasis)
텍스트 강조는 굵게, 기울림, 취소선이 존재한다.
```markdown
**(word)**
__(word)__

_(word)_
***(word)***

___(word)___

~~(word)~~
```

-----

### 6. 인용구(Quote)
인용구는 >을 사용한다. >을 추가하면 추가로 인용이 가능하다.
```markdown
> allusion 1
>> allusion 2
>>> allusion 3
```

---

### 7. 소스 코드(Sorce Code)
소스 코드의 경우 억음부호(`)을 사용한다.
```markdown
 use ```(backtick)```
```
ex) 소스코드는 ```sorce code``` 사용된다. 


---

### 8. 하이퍼링크(Hyper Link)
하이퍼링크는 3가지의 방법이 존재한다.
```markdown
1. 웹 주소 첨가

2. [링크 주소](링크 주소)

3. [링크 주소](링크 주소, "부연 설명")
```
ex)

1의 방법 : <https://github.com/nownuu>

2의 방법 : [nownuu GitHub](https://github.com/nownuu)

3의 방법 : [nownuu GitHub](https://github.com/nownuu, "DallKong♥")

-----

### 9. 이미지(image)
이미지도 하이퍼링크와 비슷한 방법으로 이미지 링크를 사용하여 첨부 가능하다.
```markdown
! [image](이미지 주소)
```
ex)
![image](https://i.pinimg.com/564x/1d/89/f1/1d89f1040d5e47fc8d8a766a9b268c51.jpg)

