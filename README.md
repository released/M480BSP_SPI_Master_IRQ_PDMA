# M480BSP_SPI_Master_IRQ_PDMA
 M480BSP_SPI_Master_IRQ_PDMA

1. SPI hw config : PB4MFP_SPI1_MOSI , PB5MFP_SPI1_MISO , PB3MFP_SPI1_CLK , PB2MFP_SPI1_SS

2. SPI clock : 800K , transmit length : 8 bytes , transmit timing : 50ms , per packet

3. Under PDMA IRQ and trigger SPI IRQ , to check SPI BUS busy or idle and TX FIFO empty and change CS pin back to high

4. Below is with SS GPIO control ,measure SS pin LOW to HIGH timing , with different DATA_NUM

![image](https://github.com/released/M480BSP_SPI_Master_IRQ_PDMA/blob/main/SS_GPIO_Timing_8bytes.jpg)

![image](https://github.com/released/M480BSP_SPI_Master_IRQ_PDMA/blob/main/SS_GPIO_Timing_16bytes.jpg)

![image](https://github.com/released/M480BSP_SPI_Master_IRQ_PDMA/blob/main/SS_GPIO_Timing_32bytes.jpg)

![image](https://github.com/released/M480BSP_SPI_Master_IRQ_PDMA/blob/main/SS_GPIO_Timing_64bytes.jpg)

![image](https://github.com/released/M480BSP_SPI_Master_IRQ_PDMA/blob/main/SS_GPIO_Timing_128bytes.jpg)

![image](https://github.com/released/M480BSP_SPI_Master_IRQ_PDMA/blob/main/SS_GPIO_Timing_256bytes.jpg)

