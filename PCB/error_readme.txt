原理图：LCD：11号脚，I2CSDA—PA55—Camera：1号引脚
PDF电路为：GPB1接到46号引脚

LCD：10号引脚，I2CSCL—PA 56—Camera：2号引脚
PDF电路为：nRESET接到PC10和MD9000的80号脚

URAT：RS232 15号引脚接地

DM9000:78,79，和60引脚关于接电阻的作用，

原理图改好了，PCB图还没改，看认真看看有没有什么错。



2012.3.28:
lcd插头改了一个地方：I2CSC->nRESET(对应PC10)
		     I2CSDA->GPB1(对应PA46)
