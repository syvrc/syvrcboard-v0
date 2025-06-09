---
title: "syvrcboard v0"
author: "@syvr"
description: "A Custom TKL Mechanical Keyboard"
created_at: "2025-06-02"
---

**Total time spent so far: 18hrs**

## First week of June: Research
> Watched hell lotta youtube videos to get a basic idea and all of what i wanted to make and how i wanted my keyboard to look like  
> I decided to go with a TKL Mechanical Keyboard layout with some customisations  

| Layout                            |
| --------------------------------- |
| ![](/assets/08%20June/layout.png) |

> The keyboard is gonna have `11 macro keys (basically integrated macropad)`, a `Rotary Encoder Switch E11`, and a `0.91inch OLED Display 128x32` and is gonna use `STM32F411CEU6 Black Pill Board` as its mcu.  

> it was REALLY painful to find out symbol and footprint of `STM32F411CEU6 Black Pill Board`  

**Time spent: 6hrs**


## 08th June: Got started
| Basic Schematic                      |
| ------------------------------------ |
| ![](/assets/08%20June/schematic.png) |
> Got done with keyboard matrix and wiring   

> Found out STM32F411CEU6 Black Pill Board on EasyEDA, converted .json files into symbol and footprint of it  
> Decided to make the keyboard Low profile since i dont really like the chunky ones(yet to finalise the switches and keycaps)  

**Time Spent: 5hrs**


## 9th June: Made the BOM
> I was tryna finalise the components and things which i was gonna work with but then found it difficult to keep a track of the money that was going into every component, so i made a BOM in `README.md` file, its currently at its second draft and is going to be updated throughout the project  

> I couldnt find a low profile keyswitch which was available in my area and was in budget, spent like 2hrs on, then researched a bit about cerry mx switches, decided to go with `Cherry MX Silent Red` but it wasnt avail in my area so then i asked for help in `#highway` and ended up with `Gateron EF Curry` switches since they are linear and LED compatible (im planning on adding LEDs to my keeb too)  

> The symbol of `STM32F411CEU6 Black Pill Board` was symboling (basically it was very buggy, like smth was wrong with it ion know what) so i chose to go with `RPI Pico` (the reason why i wasnt using it before is cuz its has micro USB interface which i didnt want to use in my keyboard but however had to cuz I ran out of options)  

> i was indecisive if i was gonna handwire my keeb or make a pcb, so i ended up watching 3 to 4 videos about handwiring but then decided to go with the pcb  

> Spent hell lotta time making the BOM and finalizing the MCU

**Time Spent: 7hrs**

<!-- ## 10th June: -->