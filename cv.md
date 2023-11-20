# Max Balashov

### Frontend Developer

---

## **Contacts**

&emsp;&emsp;&emsp;&emsp;**Email:** &emsp;&ensp;&emsp;maxballashov@gmail.com  
&emsp;&emsp;&emsp;&emsp;**GitHub:**&emsp;&emsp;[@refvds](https://github.com/refvds)  
&emsp;&emsp;&emsp;&emsp;**LinkedIn:**&emsp;&ensp;[Max Balashov](https://www.linkedin.com/in/max-balashov/)

---

## **Profile**

I am a frontend developer, inspired
by web technologies and their development. I've done several non commercial projects on React technology, including a blog, a social network, and a pizzeria. Really like the e-learning industry, as well as any LMS system I'd like to work on in the future.

---

## **Skills**

- Javascript / Typescript
- HTML / CSS (SASS, BEM-naming)
- Bundlers and task-runners (gulp / webpack / vite)
- React / Next / Redux / Zustand
- Backend (nodejs, nestjs)

---

## **Code example**

_Given a string s, find the length of the longest
substring
without repeating characters._

Example 1

> `Input: s = "abcabcbb"` \
>  `Output: 3` \
>  `Explanation: The answer is "abc", with the length of 3.`

Example 2

> `Input: s = "bbbbb"` \
>  `Output: 1` \
>  `Explanation: The answer is "b", with the length of 1.`

Example 3

> `Input: s = "pwwkew"` \
>  `Output: 3` \
>  `Explanation: The answer is "wke", with the length of 3.
Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.`

```
const lengthOfLongestSubstring = function(s) {
    const chars = new Set();
    let left = 0;
    let count = 0;

    for (let right = 0; right < s.length; right++) {
        while (chars.has(s[right])) {
            chars.delete(s[left]);
            left++;
        }
        chars.add(s[right]);
        count = Math.max(count, right - left + 1);
    }
    return count;
};
```

---

## **Education**

**Belarusian State University of Informatics and Radioelectronics (BSUIR)** - Bachelor's degree [2018 - 2022]  
_System Engineer_

---

## **Languages**

- **Belarusian** - native level
- **Russian** - native level
- **English** - pre-intermediate level

---
