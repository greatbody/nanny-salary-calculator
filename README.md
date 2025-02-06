# Nanny Salary Calculator 阿姨工资计算器

A web-based calculator for computing nanny (domestic helper) salary based on different scenarios and working days.

一个基于网页的工资计算器，用于计算家政阿姨的工资，支持多种计算场景和工作天数。

## Features 功能特点

- Calendar-based work day selection 基于日历的工作日选择
- Multiple calculation scenarios 多种计算场景:
  - Normal working month 普通工作月份
  - First month of February (first year) 二月首月（首年）
  - Special holiday months (Spring/Summer) 特殊放假月份（春季/暑期）
- Automatic rest day calculation 自动休息日计算
- Detailed salary breakdown 详细的工资计算明细

## Calculation Rules 计算规则

### Normal Month 普通月份
- Base salary: ¥5000/month 基本工资：每月5000元
- Regular rest days: 4 days/month 固定休息：每月4天
- Extra leave deduction (≤5 days): ¥190/day 额外休假扣款（≤5天）：每天190元
- Daily rate for >5 days leave: ¥195/day 超过5天休假时的日薪：每天195元

### First Month (February) 二月首月
- Daily rate: ¥200/day 每天200元

### Special Holiday Months 特殊假期月份
- Daily rate: ¥192.31/day (5000/26) 每天192.31元（5000/26）

## Usage 使用方法

1. Select calculation scenario 选择计算情形
2. For normal months 普通月份:
   - Use calendar to select working days 使用日历选择工作日
   - System automatically calculates extra leave 系统自动计算额外休假
3. For February/Special months 二月/特殊月份:
   - Input actual working days 输入实际工作天数
4. View calculated salary and details 查看计算结果和明细

## Setup 部署方法

This is a static HTML page. Simply open `index.html` in a web browser to use.

这是一个静态HTML页面，直接在浏览器中打开 `index.html` 即可使用。

## Browser Compatibility 浏览器兼容性

Supports all modern browsers (Chrome, Firefox, Safari, Edge).

支持所有现代浏览器（Chrome、Firefox、Safari、Edge）。

## AI Assistance 智能辅助

这个项目使用了 AI 辅助。
