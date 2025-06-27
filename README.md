# docker 


Docker 三種 在Windows 10 的安裝法

1. 直接裝 Docker Desktop ，會問用 Hyper-V 還是 WSL (建議值)，簡單好用，有圖形界面，但開啓很慢， WSL下會開一個 Docker-Desktop 
2. 只裝 Docker CLI ：基本是 Windows 的Container，只能跑Windows image。 不能跑 Linux
3. WSL 裏面的 Ubuntu 裝 Docker。再到PS 上用docker Context 指定到 Ubuntu 的 Docker Server (我現在用這種) 

-| ==Docker== | WSL2 | 	Hyper-V | 
--|--|--| --
Win10| V|V  | V 
WinServer2019 |V  | wsl1 | V
WinServer2021 |V  | wsl2 | V
GUI | PC有 其他外加  | X | V|
指令 | ==難/多== | 中/少 | X
Linux 直接下 |V  | V | X 下iso安裝
image # | 多 | ==少== | 少
AP image | V | x|x
耗資源 | 少 | 少 | 多
跨平臺 | V|X |X|
|  |  |
