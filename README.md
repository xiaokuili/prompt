# prompt
收集和学习prompt技能

# 分类
- llm-sql
- label
  
## zero shot
RLHF（基于人类行为反馈学习），直接提问，不提供样本
```
Classify the text into neutral, negative or positive. 
Text: I think the vacation is okay.
Sentiment:
```

## few shot
给一些案例

# reason
## few-shot， zero-shot， few-shot-cot, zero-shot-cot
- few-shot-cot: example is reason
- zero-shot-cot:let think step by step 
## auto-cot
1. 分模块
2. 每个模块进行zero-shot-cot


## 反馈，报告生成 
```
do ...
自动反馈错误并且改正
```
