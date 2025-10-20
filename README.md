# python-100-days-learning# Python 100天自学计划 🐍

> 从零开始，用100天系统学习Python编程

## 📊 学习进度（前28天自学未接触git，所以前28天文件后续有时间再整理上传）

| 项目 | 进度 |
|------|------|
| **总天数** | 30/100 天 |
| **开始日期** | 2025年9月 |
| **代码文件数** | 4个 |
| **提交次数** | 4 次 |

## 🗓️ 每日学习记录

### ✅ 已完成
- **Day 1**: 环境搭建与GitHub使用
- **Day 2**: Python基础语法入门
- **Day 3**: 函数与装饰器学习
-  **Day 29**: 面向对象
-   **Day 30**: 实例属性和构造函数
-   **Day 31**: 析构函数和封装

### 🔄 进行中
- **Day 32**: 单继承和方法的重写

### ⏳ 待学习
- 面向对象编程
- 文件操作
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

class Person:
    name = ('zz')
    def _play(self):#私有方法
        print(f'{Person.name}在玩手机')
    def __introduce(self):#隐藏方法
        print(f'我是{Person.name}')
    def func(self):
        print('这是平平无奇的实例方法')
        Person._play(self)#在实例方法中调用———不推荐(一定不要忘记self)
        Person.__introduce(self)
        self._play()
        self.__introduce()
pe = Person()
# pe._play()
# pe._Person__introduce()
pe.func()
📈 每周总结
第1周总结
学习内容: 环境搭建、GitHub使用、异常处理，闭包和装饰器，面向对象实例方法调用

完成情况: 7/7天

收获: 学会了版本控制的基本操作

最后更新: 2025年10月
每日更新，持续进步中...

坚持每天学习，100天后见证不一样的自己！
