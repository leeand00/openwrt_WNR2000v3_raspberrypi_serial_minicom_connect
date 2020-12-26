
# Openwrt WNR2000v3 Raspberry PI Serial Minicom Connect


![raspberrypi hooked up to a WNR2000v3 physical](https://github.com/leeand00/openwrt_WNR2000v3_raspberrypi_serial_minicom_connect/blob/develop/forum/Debricking%20WNR2000v3%20with%20Raspberry%20PI%20and%20a%20serial%20connection_%20-%20Hardware%20Questions%20and%20Recommendations%20-%20OpenWrt%20Forum_files/2KiQz.jpg?raw=true)

![raspberrypi headers](https://github.com/leeand00/openwrt_WNR2000v3_raspberrypi_serial_minicom_connect/blob/develop/forum/Debricking%20WNR2000v3%20with%20Raspberry%20PI%20and%20a%20serial%20connection_%20-%20Hardware%20Questions%20and%20Recommendations%20-%20OpenWrt%20Forum_files/p1header.png?raw=true)


| Pi Side |               |            | 10K Resistor (end 1) | 10K Resistor (end 2)                       | WNR2000v3 Side |
|---------|---------------|------------|----------------------|--------------------------------------------|----------------|
|   Pin   |  Signal Name  | Wire Color |                      |                                            |                |
|    1    | 3.3 VDC Power | Orange     |  connect to this end | 10 RxD (UART) Pi Side                      |                |
|    6    | 0V (Ground)   | Black      |          N/A         |                     N/A                    | Ground         |
|    8    | TxD (UART)    | Yellow     |          N/A         |                     N/A                    | RxD (UART)     |
|    10   | RxD (UART)    | Blue       |          N/A         | connect back from  1 3.3 VDC Power Pi Side | TxD (UART)     |
