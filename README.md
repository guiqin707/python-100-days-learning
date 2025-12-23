# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 89/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 62个 |
| **提交次数** | 62 次 |

## 🗓️ 每日学习记录

### ✅ 已完成
- **Day 1**: 环境搭建与GitHub使用
- **Day 2**: Python基础语法入门
- **Day 3**: 函数与装饰器学习
- **Day 29**: 面向对象
- **Day 30**: 实例属性和构造函数
- **Day 31**: 析构函数和封装
- **Day 32**: 单继承和方法的重写
- **Day 33**: 新式类写法和多继承
- **Day 34**: 多态、静态方法和类方法
- **Day 35**: 单例模式&魔法方法（1）
- **Day 36**: 单例模式&魔法方法（2）
- **Day 37**: 文件的基本操作，文件读写
- **Day 38**: 访问模式，文件定位操作
- **Day 39**: with、open&编码格式、获取目录操作
- **Day 40**: 可迭代对象、迭代器对象
- **Day 41**: 可迭代、迭代器&自定义迭代器类
- **Day 42**: 生成器、三者关系
- **Day 43**: 多任务、简单多线程的实现和多线程的方法
- **Day 44**: 多线程的特点与同步、互斥锁
- **Day 45**: 进程的常用方法和属性
- **Day 46**: 进程的代码结构、之间的通信和进程操作队列
- **Day 47**: 进程池，同步和异步，进程池通信的示例
- **Day 48**: 协程操作和greenlet使用
- **Day 49**: gevent使用和总结
- **Day 50**: 正则表达式、匹配单个字符
- **Day 51**: 匹配多个字符、匹配开头结尾
- **Day 52**: 匹配分组
- **Day 53**: 高级用法、贪婪与非贪婪和原生字符串
- **Day 54**: os模块、sys模块
- **Day 55**: time和loggin模块
- **Day 56**: random模块
- **Day 57**: 练习题1
- **Day 58**: 练习2
- **Day 59**: 练习3
- **Day 60**: 练习4
- **Day 61**: 练习5
- **Day 62**: 练习6
- **Day 63**: 练习7
- **Day 64**: 练习8
- **Day 65**: 练习9
- **Day 66**: 练习10
- **Day 67**: 练习11
- **Day 68**: 练习12
- **Day 69**: 练习13
- **Day 70**: 练习14
- **Day 71**: 练习15
- **Day 72**: 练习16
- **Day 73**: 练习17
- **Day 74**: 练习18
- **Day 75**: 练习19
- **Day 76**: 练习20
- **Day 77**: 练习21
- **Day 78**: 练习22
- **Day 79**: 练习23
- **Day 80**: 练习24
- **Day 81**: 练习25
- **Day 82**: 练习26
- **Day 83**: 练习27
- **Day 84**: 练习28
- **Day 85**: pandas1
- **Day 86**: pandas2
- **Day 87**: numby1
- **Day 88**: numby2
- **Day 89**: matplotlib1
- 

### 🔄 进行中
- **Day 90**: matplotlib2
### ⏳ 待学习
- 面向对象编程
- 网络请求
- 数据库连接
- 实战项目开发

## 📁 项目结构
py100days/
├── 01_basics/ # 第1-15天：Python基础
├── 02_data_structures/ # 第16-35天：数据结构
├── 03_oop/ # 第36-50天：面向对象
├── 04_advanced/ # 第51-80天：进阶主题
├── 05_projects/ # 第81-100天：实战项目
└── resources/ # 学习资源

## 🎯 学习目标

- [ ] 掌握Python核心语法
- [ ] 理解常用数据结构与算法
- [ ] 能够独立完成小型项目
- [ ] 建立良好的编程习惯
- [ ] 准备技术面试

## 📚 学习资源

https://space.bilibili.com/3546597933714079?spm_id_from=333.788.upinfo.head.click

## 💻 今日代码示例

import matplotlib.pyplot as plt
import numpy as np

# x = np.array([2023, 2024, 2025, 2026])
# y1 = np.array([20, 23, 26, 30])
# y2 = np.array([22, 21, 26, 18])
# y3 = np.array([15, 18, 36, 20])
# line_styles = dict(marker='.',
#          markersize=30,
#          markerfacecolor='#365083FF',
#          # markeredgecolor='#B783AFFF',
#          markeredgewidth=1,
#          linestyle='solid',
#          linewidth=4)
# #B783AFFF
# #F5A673FF
# #FCDB72FF
# plt.plot(x, y1, color='#B783AFFF', **line_styles)
#
#
# plt.plot(x, y2, color='#F5A673FF', **line_styles)
#
#
# plt.plot(x, y3, color='#FCDB72FF', **line_styles)
#
#
# plt.title("Class sizes",
#           fontsize=20,
#           fontweight='bold',
#           family='Times New Roman',
#           color='#F5A673FF')
#
# plt.tick_params(axis='both')
# plt.xlabel("Year",
#            fontsize=20,
#           fontweight='bold',
#           family='Times New Roman',
#           color='#F5A673FF')
#
# plt.ylabel("Student size",
#            fontsize=20,
#           fontweight='bold',
#           family='Times New Roman',
#           color='#F5A673FF')
#
# plt.xticks(x, family='Times New Roman')
# plt.yticks(family='Times New Roman')
# plt.show()
#
# plt.figure(figsize=(8, 5))
# x = [0, 1, 2, 3, 4, 5]
# y = [0, 1, 4, 9, 16, 25]
#
# plt.plot(x, y)

# 设置x轴刻度的位置和标签
# plt.xticks(
#     ticks=[0, 2, 4],                    # 显示刻度的位置
#     labels=['起点', '中间', '终点'],     # 对应位置的标签
#     fontsize=14,                        # 字体大小
#     fontweight='bold',                  # 字体粗细
#     color='blue',                       # 标签颜色
#     rotation=45,                        # 标签旋转角度
#     fontname='Times New Roman'          # 字体名称
# )
#
# plt.show()
# 使用 plt.tick_params() 当你需要：
# 调整刻度的样式（长度、宽度、颜色）
# 控制刻度线的方向（向内/向外）
# 批量设置x轴和y轴的样式
# 控制刻度标签的显示位置
#
# 使用 plt.xticks() 当你需要：
# 自定义刻度的位置
# 修改刻度标签的文本内容
# 设置具体的字体名称、样式
# 旋转刻度标签


# 设置网格线

# x = np.array([1, 2, 3, 4, 5])
# y = np.array([11, 21, 33, 41, 51])
# plt.grid(axis='y', linestyle='--', linewidth=2,
#          color='lightgray')
#
#
# plt.plot(x, y)
#
# plt.show()


# 条形图

# categories = np.array(['apple', 'banana', 'cherry', 'orange'])
# values = np.array([21, 22, 28, 15])
#
# plt.bar(categories, values, color='#365083FF')
# plt.barh(categories, values, color='#365083FF')#水平条形图
# plt.title("Fruit",
#           family= 'Times New Roman',
#           color = 'blue',
#             fontsize=20 )
#
# plt.xlabel("Category", family= 'Times New Roman',
#           color = 'blue',
#             fontsize=20)
# plt.ylabel("Value", family= 'Times New Roman',color = 'blue',
#             fontsize=20)
#
# plt.xticks(family= 'Times New Roman')
# plt.yticks(family= 'Times New Roman')

# plt.show()


# 饼图
categories = np.array(['apple', 'banana', 'cherry', 'orange'])
values = np.array([21, 22, 28, 15])
colors = ['#365083FF', '#B783AFFF', '#F5A673FF', '#FCDB72FF']

plt.pie(values, labels=categories,
        autopct='%1.1f%%',
        startangle=90,
        colors=colors,
        shadow=True,
        explode=(0, 0, 0.1, 0),
        textprops={
            'fontname': 'Times New Roman',  # 设置字体
            'fontsize': 12,  # 字体大小
            'fontweight': 'normal',  # 字体粗细
            'color': 'black'  # 字体颜色
        } )

plt.show()


📈 每周总结
第11周总结
学习内容:做笨方法学习python的习题，巩固基础

完成情况: 1/7天

收获:学到了大概的pandas和numby
最后更新: 2025年12月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
