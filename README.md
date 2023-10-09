# TPSGame
第三人称射击类的游戏

[相关脚本](https://github.com/dyx77421088/TPSGameScript)

# 加载界面
## 进入游戏首先检测更新
![更新](https://github.com/dyx77421088/TPSGame/assets/46596598/e9fe9ba5-8baa-4cf6-8c9e-cffce3d14b95)
![更新2](https://github.com/dyx77421088/TPSGame/assets/46596598/acdb1ee4-ded2-409c-8654-c8fd59766b5c)
https://github.com/dyx77421088/TPSGameScript/assets/46596598/3b4018b8-72f4-4c8b-a0a5-2a6c0fdb6832
# 角色状态机
## 角色主要有三种状态，为无武器状态、枪、剑。
![角色控制器1](https://github.com/dyx77421088/TPSGame/assets/46596598/3771308f-1b0a-49f1-a406-b862118f703a)
## 在枪状态中包括有，行走的混合树、跑状态的混合树、跳跃状态
![角色控制器2](https://github.com/dyx77421088/TPSGame/assets/46596598/4d05bdf7-14cf-4b13-a85a-0146477edb33)
### 通过输入横轴和纵轴控制角色的移动
![混合树1](https://github.com/dyx77421088/TPSGame/assets/46596598/be59f882-50e6-4087-988e-d8b8f2b0b5fb)  ![混合树2](https://github.com/dyx77421088/TPSGame/assets/46596598/c4bed4ae-926d-4091-85ac-7fad9be05b81)

## 在剑状态中包括有，行走的混合树、跑状态的混合树、跳跃状态、攻击状态
![剑攻击1](https://github.com/dyx77421088/TPSGame/assets/46596598/473b7177-f65d-4fd9-ade5-c3b729807fb6)
### 攻击状态中，包括有普通攻击、跑状态下点击攻击、技能攻击
![剑攻击2](https://github.com/dyx77421088/TPSGame/assets/46596598/a2e1656d-cf7e-428f-a4cf-925ac458f30b)
### 普通攻击分为三段、在短时间内点击攻击会连续打出三段攻击
![剑攻击3](https://github.com/dyx77421088/TPSGame/assets/46596598/f29feb78-3893-41f3-b9bb-09e26c5108a2)

