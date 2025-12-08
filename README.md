# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 75/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 48个 |
| **提交次数** | 48 次 |

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
- 

### 🔄 进行中
- **Day 75**: 练习19
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

# # 文件名：adventure_game.py
# print("You enter a dark room with two doors. Do you go through door #1 or door #2?")
#
# door = input(">")
#
# if door == "1":
#     print("There's a giant bear here eating a cheese cake. What do you do ?")
#     print("1. Take the cake.")
#     print("2. Scream at the bear.")
#
#     bear = input(">")
#
#     if bear == "1":
#         print("The bear eats your face off. Good job!")
#     elif bear == "2":
#         print("The bear eats your legs off. Good job!")
#     else:
#         print(f"Well, doing {bear} is probably better. Bear runs away.")
#
# elif door == "2":
#     print("You stare into the endless abyss at Cthulhu's retina.")
#     print("1. Blueberries.")
#     print("2. Yellow jacket clothespins.")
#     print("3. Understanding revolvers yelling melodies.")
#
#     insanity = input(">")
#
#     if insanity == "1" or insanity == "2":
#         print("Your body survives powered by a mind of jello. Good job!")
#     else:
#         print("The insanity rots your eyes into a pool of muck. Good job!")
#
# else:
#     print("You stumble around and fall on a knife and die. Good job!")

# def dark_room_game():
#     """黑暗房间 - 演示嵌套if语句"""
#     print("=" * 60)
#     print("欢迎来到黑暗房间冒险游戏！")
#     print("=" * 60)
#     print("\n你进入了一个黑暗的房间，面前有两扇门。")
#     print("你会选择1号门还死2号门")
#
#     door = input("请输入 1 或 2 ：").strip()
#
#     if door == "1":
#         print("\n你选择了1号门...")
#         print("里面有一个美杜莎雕像，雕像前面有一个宝箱！你会怎么做？")
#         print("1. 转头离开")
#         print("2. 小心上前并打开宝箱看里面有什么好东西")
#         print("3. 大喊大叫")
#
#         action = input("请输入你的选择（1-3）：").strip()
#         if action == "1":
#             print("\n你走得太快，踩到了机关，被乱箭射死。干得漂亮！")
#         elif action == "2":
#             print("\n你打开了宝箱，触碰到了机关，雕像苏醒，把你变成石人。干得漂亮！")
#         elif action == "3":
#             print("\n你把隔壁吃奶酪的熊引过来了，熊的动静惊动了机关和雕像，熊被射死并且变成石头，你拍怕心脏，小心的离开了房间。明智的选择！")
#         else:
#             print(f"\n你选择了{action}, 什么都没有发生。")
#     elif door == "2":
#         print("\n你选择了2号门...")
#         print("你凝视着克苏鲁无尽的深渊视网膜")
#         print("\n你选择了2号门...")
#         print("你凝视着克苏鲁无尽的深渊视网膜。")
#         print("1. 蓝莓")
#         print("2. 黄色夹子")
#         print("3. 理解左轮手枪在吼叫旋律")
#
#         insanity = input("请输入你的选择 (1-3): ").strip()
#
#         if insanity in ["1", "2"]:
#             print("\n你的身体存活下来，但心智变成了果冻。干得漂亮!")
#         elif insanity == "3":
#             print("\n你理解了左轮手枪的旋律，获得了超能力!")
#         else:
#             print("\n疯狂腐蚀了你的眼睛，变成了一滩污泥。干得漂亮!")
#
#     else:
#         print("\n你犹豫不决，在黑暗中绊倒，摔在刀子上死了。干得漂亮!")
#
# if __name__ == "__main__":
#     dark_room_game()
📈 每周总结
第9周总结
学习内容:做笨方法学习python的习题，巩固基础

完成情况: 7/7天

收获: 临近期末考试，百忙之中还在坚持写，复习了if else 和函数
最后更新: 2025年12月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
