

fpga:
	@echo "Building FPGA project..."
	@echo ""
	@bash ../../modules/xilinx_npf_buildflow/xilinx_npf_buildflow.sh
	@chmod 777 -R *

clean:
	@echo "Cleaning FPGA project..."
	@echo ""
	@rm -rf vivado*
	@rm -rf .Xil 
	@rm -rf *.txt 
	@rm -rf spnr 
	@rm -rf img
	@rm -rf logs

.PHONY: fpga clean
