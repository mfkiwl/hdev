TARGET=ip
DEVICE=xcv80-lsva4737-2MHP-e-S

all:
	vitis_hls build.tcl -tclargs $(TARGET) $(DEVICE) dma
	vitis_hls build.tcl -tclargs $(TARGET) $(DEVICE) offset

clean:
	rm -r build_$(TARGET) vitis_hls.log