# Sobel Edge Detection System with FGPA 
![image](https://github.com/user-attachments/assets/fd6eff4e-ab69-41b2-a017-66208e638eda)





## What are Sobel Edge Detection Systems? 
A technique highly involved in computer processing and computer vision. It can help create image processing and
computer vision using edge detection algorithmns. This acts as a discrete differentiation operator and it involves 
using 3x3 kernels as shown below. 


## Programs 
> Xlinix (ARTY Z7)
> Vivado (ARTY Z7)
> iceStick Evaluation

### Embedded Chip 

### FGPA Modulation 
Repo2Txt
// This makes all the FGPA LED Lights power on: 
module leds(output wire D1, 
            output wire D2, 
            output wire D3,  
            output wire D4, 
            output wire D5); 

assign D1 = 1'b1;
assign D2 = 1'b1;
assign D3 = 1'b1;
assign D4 = 1'b1;
assign D5 = 1'b1;

endmodule 

## Embedded Chips vs. FGPA 
There are various ways that a Sobel Edge Detection can be done. It can be done through a chip Embedded System or a (FGPA) which is a 
circuit customized for a specific applications. 


![image](https://github.com/user-attachments/assets/31798fd0-1380-4bae-ac95-9960e7de45f5)



FGPA: The advantage of the FGPA circuit model is its fast usage and integration of parallel circuit systems. It can virtual cells that can be inolved in the creation of logical arrays 
making it faster than hardware chip processors. They do rely on HLDs which assign a gate to a boolean operator and can link several gates together. 

## ice40 Lp/Hx 2.1 Pinout Excel file
[Excel File] https://fiudit-my.sharepoint.com/:x:/r/personal/jgonz1399_fiu_edu/Documents/iCE40PinoutHX1K.xlsx?d=wec95994da6e4476abe0c995e11ac5249&csf=1&web=1&e=wnt0s3




###### Resources & Citations 
- https://techterms.com/definition/fpga#:~:text=An%20FPGA%20is%20an%20integrated%20circuit%20that%20can,blocks%20that%20can%20be%20wired%20in%20different%20configurations.
- https://www.erhardt-leimer.com/global/en/products/measuring-technology/measuring-systems-for-the-tire-industry/el-edge-detection-by-laser-triangulation.html?utm_medium=sea&utm_source=bing&utm_campaign=SRC-Generic-Produkte-USA/Oceania&utm_content=edge%20detection%20production&msclkid=e7bc02392931105c52ca65d0bde4d713
