# 常用负面词与约束库

## 使用场景

适用于所有商业 AIGC 视觉任务，尤其是产品图、包装、IP、人像和 KV。

## 原始需求

建立一组可复制的负面约束，减少变形、跑偏、乱码和廉价感。

## Prompt

通用负面约束：不要改变主体比例、构图、角度、品牌 Logo、包装文字、产品结构、角色身份、人物五官和原始色彩关系。不要新增无关元素，不要文字乱码，不要边缘破损，不要塑料感，不要过度锐化，不要 AI 涂抹感，不要廉价滤镜，不要背景杂乱，不要主体漂浮，不要错误阴影，不要风格混杂。

## 负面词

logo distortion, wrong text, unreadable text, deformed product, changed proportions, identity drift, plastic texture, dirty texture, over sharpened, blurry edge, floating object, wrong shadow, cluttered background, cheap template style.

## 修改指令

- 产品变形：锁定主体比例、结构、角度和包装信息。
- 文字错误：要求文字区域保持不变，或改为后期排版留白。
- 画面廉价：减少装饰，强化真实光影和商业摄影质感。

## 注意事项

负面词要跟任务相关，不要无限堆叠。最重要的约束应放在 Prompt 开头。

## 效果评分

9/10：适合作为通用安全约束模块。

## 修改记录

- v01：整理商业视觉常用负面约束。

