.PHONY:clean all

all:i2c-rtc.dtbo

i2c-rtc.dtbo:i2c-rtc-overlay.dts
	dtc -q -I dts -O dtb -o $@ $^

clean:
	rm -rf *.dtbo
