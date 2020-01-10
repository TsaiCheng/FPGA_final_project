# FPGA_final_project

Author:107321015, 107321022, 107321034

功能說明:
俄羅斯方塊遊戲，掉下來的方塊可以左右移動、加速降落、旋轉，若最底層排滿了則消除，方塊疊到最上層則結束遊戲。

腳位說明:
module LED8x8(DATA_R,DATA_G,DATA_B,COMM,a,b,c,d,e,f,g,CLK,left,right,speed,rotation,clear,timeout);

Data_G,Data_B,Data_R為8*8LED輸出腳位
CLK為時脈
left為方塊向左移動
right為方塊向右移動
rotation為使方塊旋轉
clear為重新開始


Video:
https://drive.google.com/open?id=1UT-3l_J21z1iDEMvT0lUGq7mtvoWDRLP
