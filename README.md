# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 44/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 17个 |
| **提交次数** | 17 次 |

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
-  **Day 44**: 多线程的特点与同步、互斥锁

### 🔄 进行中
- **Day 45**: 线程特点
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

# 导入模块
from threading import Lock
import threading
# 1.创建全局互斥锁
lock = Lock()
a = 0
b = 10000000
def add():
    #上锁
    lock.acquire()
    for i in range(b):
        global a
        a += 1
    print('第一次累加：',a)
    #释放锁
    lock.release()
def add1():
    #上锁
    lock.acquire()
    for i in range(b):
        global a
        a += 1
    print('第二次累加：',a)
    #释放锁
    lock.release()
if __name__ == '__main__':
    ad = threading.Thread(target=add)
    ad1 = threading.Thread(target=add1)
    ad.start()
    ad1.start()
📈 每周总结
第6周总结
学习内容: 封装，父类和子类继承，魔法方法，文件操作

完成情况: 7/7天

收获: 学会了什么是迭代器，生成器和它们与可迭代对象之间的关系；线程
最后更新: 2025年11月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
