# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 81/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 54个 |
| **提交次数** | 54 次 |

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
- 

### 🔄 进行中
- **Day 82**: 练习26
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

print("=== 字典基础练习 ===")

# 1.创建不同类型的字典
print("\n. 创建不同类型的字典：")

# 字典串键
student = {"name": "guigui", "age": 18, "major": "生物学"}
print(f"学生信息：{student}")

# 整数键
phonebook = {1001:"李四", 1002: "zz"}
print(f"电话簿：{phonebook}")

# 混合类型键
mixed_dict = {"name": "huihui", 123: "学号", 3.14: "圆周率", True: "布尔值"}

# 嵌套字典
company = {
    "name": "科技公司",
    "departments": {
        "engineering": ["guigui", "zz"],
        "sales": ["100w", "500w"],
        "hr": ["hh", "nn"]
    },
    "location": "Shanghai"
}
print(f"公司信息：{company}")

# 2.字典操作
print("\n2. 字典操作：")

# 检查键是否存在
print(f"'name' 在 student中吗？{'name' in student}")
print(f"'salary' 在 student 中吗？{'salary' in student}")

# 获取所有键值
print(f"所有键：{list(student.keys())}")
print(f"所有值：{list(student.values())}")
print(f"所有键值对：{list(student.items())}")


# 字典长度
print(f"字典长度：{len(student)}")

# 3.遍历字典
print("\n3. 遍历字典：")

print("遍历键：")
for key in student:
    print(f"{key}:{student[key]}")

print("遍历键值对：")
for key, value in student.items():
    print(f" {key}: {value}")

print("遍历值：")
for value in student.values():
    print(f"值：{value}")

# 4.字典推导式
print("\ns. 字典推导式：")

# 创建平方字典
numbers = [1, 2, 3, 4, 5]
squares = {x : x**2 for x in numbers}
print(f"平方字典：{squares}")

# 过滤字典
student_scores = {"zz": 100, "guiigui": 89, "hh": 98}
good_scores = {name: score for name, score in student_scores.items() if score >= 90}
print(f"高分学生：{good_scores}")

# 5.字典合并
print("\n5. 字典合并：")

dict1 = {"a": 1, "b": 2}
dict2 = {"c": 3, "d": 10}

# 法一 update()
dict1.update(dict2)
print(f"使用update合并：{dict1}")

# 法2字典拆包
dict1 = {"a": 1, "b": 2}
merged = {**dict1, **dict2}
print(f"使用拆包合并：{merged}")

# 法3：管道操作符
merged = dict1 | dict2



📈 每周总结
第9周总结
学习内容:做笨方法学习python的习题，巩固基础

完成情况: 6/7天

收获: 临近期末考试，百忙之中还在坚持写，复习了if else 和函数
最后更新: 2025年12月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
