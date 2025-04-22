# FPGA-Powered-Acceleration-of-MobileNet-V1
Hardware accelerator design

Note: ALl zipped files are uploaded. DOwn or clone the repository file and unzip them to see sub folders and sub files.

Three steps are followed to implement or complete this project.

![image](https://github.com/user-attachments/assets/31d6a4f9-b9c7-4007-8339-679b2cee37c9)

Implementation flow:
The proposed research work considers the execution in three parallel workows as listed below:
1. Software design level (Training the model and extracting weights from the saved model).
2. Hardware design level (Overlay design using Vitis HLS tool and VIVADO IP integration
tool).
3. Hardware implementation level (ZCU104) board setup, overlay instantiation,
memory allocation, and loading data.

Tool to be used :
Vitis HLS tool for designing the IP and exporting it as RTL IP.
Vivado Tool for integrating the generated IP from Vitis HLS tool with the zynq processor and generating the bit stream file.

For further easy steps can refer below paper:
https://link.springer.com/article/10.1007/s10617-023-09274-8
https://onlinelibrary.wiley.com/doi/full/10.1002/cta.3957

Google scholar id:https://scholar.google.com/citations?user=5ogIuhAAAAAJ&hl=en




