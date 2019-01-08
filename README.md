# Tetris 
## A Tetris Battle Game on FPGA
- Language : SystemVerilog
- Development Environment : Quartus 13.1

## User Interface
- 4 bit button input : 左右移動、旋轉方塊、加快下落速度
- 8X8 RGB 顯示遊戲畫面
- LED 消去行數進度條
- 七段顯示器顯示等級

## 基本功能
- 隨機出現一種方塊
- 碰到底部或堆疊的方塊會停止 
- 下落中的方塊可左右移動、轉向、加速 
- 橫排填滿時會消掉，上面方塊向下填補 
- 堆疊方塊碰到頂部的時候結束遊戲

## 進階功能
- 可踢轉
- 進度條滿時晉級
- 方塊落下速度隨等級增加
- Game Over 時顯示 windows :( 表情
