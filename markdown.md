# 마크다운 문법

<br />

## 1. 제목

<br />

# 제목1 - H1

## 제목2 - H2

### 제목3 - H3

#### 제목4 - H4

##### 제목5 - H5

###### 제목6 - H6

```
# 제목1 - H1
## 제목2 - H2
### 제목3 - H3
#### 제목4 - H4
##### 제목5 - H5
###### 제목6 - H6
```

<br />

---

<br />

## 2. 순서있는 목록

<br />
  
1. 첫번째 아이템  
   1. 하위 아이템
        1. 하위 아이템
2. 두번째 아이템
3. 세번째 아이템

<br />

```
1. 첫번째 아이템
   1. 하위 아이템
        1. 하위 아이템
2. 두번째 아이템
3. 세번째 아이템
```

<br />

---

<br />

## 3. 순서없는 목록

<br />

- 첫번째 아이템
  - 1-1 아이템
  - 1-2 아이템
  - 1-3 아이템
- 두번째 아이템
  - 2-1 아이템
  - 2-2 아이템
- 세번째 아이템
  - 3-1 아이템
    - 3-1-1 아이템
  - 3-2 아이템

```
  + 첫번째 아이템
      - 1-1 아이템
      - 1-2 아이템
      - 1-3 아이템
  + 두번째 아이템
      * 2-1 아이템
      * 2-2 아이템
  + 세번째 아이템
      + 3-1 아이템
          + 3-1-1 아이템
      + 3-2 아이템
```

<br />

---

<br />

## 4. 강조

<br />

_single asterisks 이텔릭체_  
 _single underscores 이텔릭체_  
 **double asterisks 볼드체**  
 **double underscores 볼드체**  
 **_tripple underscores 볼드+이텔릭체_**  
 **_tripple underscores 볼드+이텔릭체_**  
 ~~cancelline 취소선~~  
 **~~bold cancelline 볼드+취소선~~**  
 <u>underline - 밑줄</u>

<br />

```
  *single asterisks 이텔릭체*
  _single underscores 이텔릭체_
  **double asterisks 볼드체**
  __double underscores 볼드체__
  ***tripple underscores 볼드+이텔릭체***
  ___tripple underscores 볼드+이텔릭체___
  ~~cancelline 취소선~~
  **~~bold cancelline 볼드+취소선~~**
  <u>underline - 밑줄</u>
```

<br />

---

<br />

## 5. 코드블럭

<br />

HTML

```html
<a href="https://www.psjco.com/" target="_blank">Play The Keyboard</a>
```

CSS

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

JAVA

```java
public class BootSpringBootApplication {
    public static void main(String[] args) {
        System.out.println("Hello, world");
    }
}
```

  <br />

````

 ```html
 <a href="https://www.psjco.com/" target="_blank">Play The Keyboard</a>
 ```// html 코드 강조

 ```css
 .list > li {
 position: absolute;
 top: 40px;
 }
 ```// css 코드 강조

 ```java
 public class BootSpringBootApplication {
     public static void main(String[] args) {
         System.out.println("Hello, world");
     }
 }
 ```// java 코드 강조
````

<br />

---

<br />
