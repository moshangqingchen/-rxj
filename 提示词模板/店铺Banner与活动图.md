# 店铺 Banner 与活动图提示词模板

适用于店铺首页 Banner、移动端活动入口图、平台活动报名图、外卖店铺活动图。关键是安全区、信息层级和多端裁切。

## 店铺 Banner

```text
Use case: ecommerce store banner
Asset type: {平台} store banner.

Primary request:
Create a polished store banner for {品牌/店铺/商品主题}. The banner should be suitable for {平台} store decoration and generated as a finished image with native Chinese text.

Canvas:
{尺寸}, banner ratio. Keep key content inside the central safe area.

Subject:
Feature {商品/菜品/主题元素}. Product should be clear but not overcrowded. Use side areas for atmosphere only, not critical text.

Text:
Render only the following Simplified Chinese text, verbatim:
Main headline: "{主标题}"
Subheadline: "{副标题}"
CTA/tag: "{CTA或标签}"

Layout:
Clear hierarchy: brand/theme first, core benefit second, action third. Important text centered or within safe margins. Leave enough breathing room for platform cropping.

Visual style:
{风格}: premium, clean, platform-friendly, matching {品类}.

Constraints:
No QR code, no phone number, no external platform guidance, no unauthorized logo, no random text, no cropped words, no excessive small print, no misleading discount. Avoid {禁用内容}.
```

## 活动促销图

```text
Use case: ecommerce promotion image
Asset type: {平台} promotion campaign image.

Create a high-impact promotion image for "{活动主题}" featuring {商品/品类}.

Canvas:
{尺寸}.

Text:
Render only this Simplified Chinese text:
Activity headline: "{活动主题}"
Core benefit: "{核心利益点}"
Action: "{行动文案}"
Time/rule if needed: "{时间或规则}"

Composition:
Strong central product or dish visual, large headline, high contrast, clean promotional accents. Keep all text inside safe margins. Do not place important text near edges.

Visual style:
Promotional but not chaotic; suitable for {平台}. Use colors that fit the product and activity.

Constraints:
No fake discount, no impossible promise, no QR code, no phone number, no random symbols, no unreadable tiny terms, no cropped characters.
```

## 多端安全区

| 画布 | 建议 |
| --- | --- |
| PC 宽屏 Banner | 关键文字和商品放中间 60%，两侧只放氛围 |
| 移动 Banner | 上下左右至少留 8% 安全边距 |
| 活动入口图 | 主标题不贴边，按钮区避免放关键内容 |
| 外卖活动图 | 不把满减、配送费等平台组件重复写满 |

## 信息层级

1. 活动主题或品牌主题
2. 最大利益点
3. 商品/菜品视觉
4. 行动提示
5. 时间/规则

规则说明如果太长，不适合放进图里，优先交给平台组件或商品详情页。
