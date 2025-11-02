# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 43/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 16个 |
| **提交次数** | 16 次 |

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

### 🔄 进行中
- **Day 44**: 线程特点
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

import time
import threading
def study(name):
    print(f'{name}在学习py')
    time.sleep(2)
    print(f'{name}还在学习')
def dance(name):
    print(f'{name}去跳舞')
    time.sleep(2)
    print(f'{name}跳完回来学习py')
#程序入口
if __name__ == '__main__':#判断是否直接运行当前文件
#     1.创建子线程
    te = threading.Thread(target=study,args = ('guigui',))#以元组的形式传参的时候，不用忘记“，”
    print(te)
    te1 = threading.Thread(target=dance,kwargs = {'name':'guigui'})#以字典的形式传参
# 3.守护线程，必须放在start()前面：主线程执行结束,子线程也会跟着结束
    te.daemon = True
    te1.daemon = True
# 2.开启子线程
    te.start()
    te1.start()
    # 4.阻塞主线程join():暂停的作用，等子线程执行结束后，主线程才回继续执行，必须放在start()后面
    te.join()
    te1.join()
    # 5.获取线程名字
    print(te.name)
    print(te1.name)
    # 6.更改线程名字
    te.name = "子线程1"
    te1.name = "子线程2"
    print(te1.name)
    print(te1.name)
    print('又在学习py的一天')
# 多任务是"多个程序同时运行"，多线程是"一个程序内多件事同时进行"。
📈 每周总结
第6周总结
学习内容: 封装，父类和子类继承，魔法方法，文件操作

完成情况: 6/7天

收获: 学会了方法的重写，特别是__new__方法，文件的读写和属性

最后更新: 2025年11月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
