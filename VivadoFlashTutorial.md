# Vivado Flash Tutorial
## 1. Open Hardware Manager
Flow &rArr; Open Hardware Manager  
![001](./img/001.JPG)
## 2. Open Target & connect
Open target &rArr; Auto Connect  
![002](./img/002.JPG)
![003](./img/003.JPG)
## 3. Add memory device
click right button on your device   
Add configure Memory Device &rArr; 
![004](./img/004.JPG)
And select your flash, you can figure out in the datasheet or schmatic
![005](./img/005.JPG)
![006](./img/006.JPG)

## program Device
After adding memory device, you can program device
select "OK" and continue
![007](./img/007.JPG)
Select bin/mcs file 
![008](./img/008.JPG)  
after select OK, it will program
![009](./img/009.JPG)
just wait a minute and you get a new program in your FPGA
![010](./img/010.JPG)

Ref:  
[Vivado如何生成BIN或MCS文件并烧写到FLASH中](https://blog.csdn.net/weixin_42837669/article/details/121625188)  
[申請 Xilinx 帳號、Vivado、WebPACK License 快速流程](http://media.ee.ntu.edu.tw/courses/msoc/0_zedlab0.pdf)



