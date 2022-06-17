HM_V3：温湿度节点
IR_V3：红外节点
Coor_all：协调器节点

波特率：57600
校验位：空置（NONE）
数据位：8
停止位：1

串口控制： 0：HMLED_ON
	  1：HMLED_OFF
	  2：HMLED_BLINK
	  
	  4：IRLED_ON
	  5：IRLED_OFF
	  6：IRLED_BLINK

CHANLIST=0x12
PAN_ID=0x22FF

串口输出格式：
	温湿度：{"sno":41701406,"temp":25,"humi":50}
	红   外：{"sno":41701406,"sensor":"infrared","interrupt":1}

温湿度输出学号更改位置：SampleAPP.c  475行
红外中断输出学号更改位置：SampleApp.c  502行
