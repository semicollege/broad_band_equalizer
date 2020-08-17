# 基于Zynq-7020的4G均衡器
A broad band equalizer implementing GAL-NLMS algorithm and running on Zynq-7020 Xilinx SOC.    
This is the Xilinx competition project I have done with my friend.       

# Resources
GAL.v: 初版GAL算法的verilog实现。        
GAL_NEW.v:优化版GAL算法的verilog实现。    
report.pdf: 详细设计报告。
    

---
# More
NLMS part is not provided, it is running on ARM dule core, writing by C++.   
You can get a video introduction of this project if you understand Chinese:     
[项目最终展示](https://v.youku.com/v_show/id_XNTczODM1MzUy.html)      
[2小时视频讲解](https://www.bilibili.com/video/BV1p54y1e7kX/)
      
---
GAL-NLMS算法图示:    
![](https://github.com/stephenkung/broad_band_equalizer/blob/master/GAL-NLMS.png)
