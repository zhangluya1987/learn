# 作业说明

```go
1.基础运行测试
    === RUN   TestCase1
    elevator_test.go:13: 总楼层期望值是5,实际也是5,符合预期.
    elevator_test.go:20: 第1的电梯期望状态是-1,实际也是-1,符合预期
    elevator_test.go:20: 第2的电梯期望状态是-1,实际也是-1,符合预期
    elevator_test.go:20: 第3的电梯期望状态是-1,实际也是-1,符合预期
    elevator_test.go:20: 第4的电梯期望状态是-1,实际也是-1,符合预期
    elevator_test.go:20: 第5的电梯期望状态是-1,实际也是-1,符合预期
    --- PASS: TestCase1 (0.00s)
    === RUN   TestCase2
    我要去3层.
    电梯开门.
    人进入电梯啦,但是没有人按目标楼层按键。
    电梯关门.
    电梯暂停.
        elevator_test.go:37: 电梯停靠在3层,按目标楼层键的人数为0,电梯暂停中。
    --- PASS: TestCase2 (0.00s)
    === RUN   TestCase3
    送人去4层
    电梯开门.
    电梯关门.
    电梯暂停.
    继续原方向前进.
    当前在4层
    送人去2层
    电梯开门.
    电梯关门.
    电梯暂停.
    继续原方向前进.
    当前在2层
    --- PASS: TestCase3 (0.00s)
    === RUN   TestCase4
    送人去4层
    电梯开门.
    电梯关门.
    电梯暂停.
    继续原方向前进.
    当前在4层
    送人去5层
    电梯开门.
    电梯关门.
    电梯暂停.
    继续原方向前进.
    当前在5层
    送人去2层
    电梯开门.
    电梯关门.
    电梯暂停.
    继续原方向前进.
    当前在2层
    送人去2层
    电梯开门.
    电梯关门.
    电梯暂停.
    继续原方向前进.
    当前在2层
    --- PASS: TestCase4 (0.00s)
    PASS

2.问题:
    - 1.case3/case4写不动了 求指导。
    - 2.代码写到最后 实在改不动了，没有特别好的思路，希望课堂讲下这个作业实现。
    - 3.bug很多 后面重写。
```