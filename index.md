---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

Hello my name is Daniel Maku and this is my System On Chip project . Aim to get the viewer interested in what follows! Guideline: 1 or 2 sentences. 


## **Template VGA Design**

## **Weekly update - 1**

this week I configured the code to put out a nigerian flag. when I first done it the shades of green were off so I had to find the binary code combination to get the perfect shade of green that I needed.
After that i decided to try figure out how to put 2 flags to display on rotation. Using a clock cycle and if a statement is true figuration.

<img width="486" height="355" alt="image" src="https://github.com/user-attachments/assets/d1b257b8-c0a8-4759-9f58-89a9f852de17" /> <img width="536" height="293" alt="image" src="https://github.com/user-attachments/assets/7aae2532-2c9e-4f54-98fb-84c3ee1b8e37" />



## **Weekly update - **
used a cycle to have the nigerian and french flag to display on rotation after a number of seconds. Attempting to start a 3rd image to the rotation which is an optical illusion.
the flag wasnt changing as quick as i wanted so i had to adjust the clock to a different configuration. CLK_HZ = 250000005 MHz clock from clk25.
<img width="536" height="293" alt="image" src="https://github.com/user-attachments/assets/0ef6cea5-1536-43f4-b0a5-e5f26dc845e8" />  <img width="584" height="317" alt="image" src="https://github.com/user-attachments/assets/b46d0f4e-9338-4242-a124-7046489358b8" />

## **Weekly update - **
added a 3rd screen on the rotation which uses checkered boxes to display by seeing if its an even or odd number by the rows and columns. next i will try to make it move.
<img width="538" height="354" alt="image" src="https://github.com/user-attachments/assets/8aad86a4-084e-4d30-98a0-774f16bfb9f9" />





### **Project Set-Up**
Summarise the project set-up and design flow. Include a screenshot of your own set-up, for example see the image of my Project Summary window below. Guideline 1 short paragraph.

<img width="1375" height="618" alt="image" src="https://github.com/user-attachments/assets/76f64b4f-2ea4-4c1c-981e-1cb3822d738e" />

### **Template Code**
Outline the structure and design of the Verilog code templates you were given. What do they do? Include reference to how a VGA interface works. Guideline: 2/3 short paragraphs, consider including screenshot(s).
### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).
### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
