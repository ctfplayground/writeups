# fuckn't


#### Category: rev
#### Points: 111

We are given a js file full of brackets. This is obfuscated using jsfuck obfuscator. So we use jsunfuck to get unfucked output.

```js
[]["f"+([!1]+[][[[].filter["constructor"]("return(isNaN+false).constructor.fromCharCode(119,97,116,101,118,114,123,106,97,118,97,115,99,114,105,112,116,95,105,115,95,97,95,49,97,110,103,117,97,103,51,95,102,48,114,95,105,110,116,51,49,49,51,99,116,117,97,49,115,125)")()]])["10"]+"lter"]["constructor"]("return alert")()([].filter["constructor"]("return(isNaN+false).constructor."+420302320151902["toString"]("31")["split"](3)["join"]("C")+"de("+"73false39false109false32false115false111false114false114false121false32false68false97false118false101false44false32false73false39false109false32false97false102false114false97false105false100false32false73false32false99false97false110false39false116false32false100false111false32false116false104false97false116"["split"](!1)+

")")());

```

Even the unfucked output is not very readable. But we can see there are some numbers in the output. These numbers look ascii. Let's take a look.

```js
>String.fromCharCode(119,97,116,101,118,114,123,106,97,118,97,115,99,114,105,112,116,95,105,115,95,97,95,49,97,110,103,117,97,103,51,95,102,48,114,95,105,110,116,51,49,49,51,99,116,117,97,49,115,125)
"watevr{javascript_is_a_1anguag3_f0r_int3113ctua1s}"
```
