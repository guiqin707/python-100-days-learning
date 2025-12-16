# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 82/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 55个 |
| **提交次数** | 55 次 |

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
- 

### 🔄 进行中
- **Day 83**: 练习27
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

print("=== 三种获取数据的方式 ===")
print()

# 1.字典方式
print("1. 字典（Dictionary）:")
mystuff_dict = {'apple': "I AM APPLES!", 'tangerine': "living reflection of a dream"}
print(f"字典获取：mystuff_dict['apple'] = {mystuff_dict['apple']}")
print()

# 2.模块方式
print("2. 模块（Module):")
print("   假设有一个mystuff.py 文件， 内容如下：")
print("    #mystuff.py")
print("   def apple():")
print("        print('I AM APPLES!')")
print("    tangerine = 'Living reflection of a dream'")
print()
print("    使用方式：")
print("    import mystuff")
print("     mystuff.apple()")
print("     print(mystuff.tangerine)")
print()

# 3.类方式
print("3. 类 (Class):")
class Mystuff:
    def __init__(self):
        self.tangerine = "And now a thousand years between"

    def apple(self):
        print("I AM APPLES!")

thing = Mystuff()
thing.apple()
print(f"类获取： thing.tangerine = {thing.tangerine}")
print()

# 比较相似之处

print("=== 相似之处 ===")
print("这方式都提供了一种从’容器‘中获取数据的方式：")
print("1. 字典：通过键获取值")
print("2.模块：通过属性名获取")
print("3. 类：通过实例属性获取")



📈 每周总结
第10周总结
学习内容:做笨方法学习python的习题，巩固基础

完成情况: 1/7天

收获: 临近期末考试，百忙之中还在坚持写，复习了if else 和函数
最后更新: 2025年12月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
