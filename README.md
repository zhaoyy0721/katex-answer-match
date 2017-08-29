# katex-answer-match

[![Build Status](https://travis-ci.org/guanghetv/katex-answer-match.svg?branch=master)](https://travis-ci.org/guanghetv/katex-answer-match)

npm install katex-answer-match

### 前端

```javascript
import judge from 'katex-answer-match'
judge.katex_answer_match(' 123', '123') // ('课程内容', '用户输入')
```


### 后端

```javascript
const judge = require('katex-answer-match')
judge.katex_answer_match(' 1 23 ', '123') // ('课程内容', '用户输入')
```