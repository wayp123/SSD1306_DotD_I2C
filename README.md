# SSD1306_DotMatrixDisplay_I2C
 
Tested NUCLEO-F767ZI development boad project that Builds when imported to STM32CubeIDE.
https://github.com/4ilo/ssd1306-stm32HAL

https://www.aliexpress.com/item/1005006100836064.html selected 4pin I2C version, 9Hz

VSS 3.3V (CN11-16) VDD Gnd (CN11-71), SCL=PB8(CN12-3), SDA=PB9(CN12-5) 

#define SSD1306_I2C_ADDR        0x78
#define SSD1306_WIDTH           128
#define SSD1306_HEIGHT          64
