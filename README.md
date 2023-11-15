# Ex09 Event Registration Web Application
## Date: 26/11/23

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
HTML:
```
<div style="width: 100%; height: 100%; position: relative; background: linear-gradient(180deg, #1930AC 50%, rgba(25.77, 49.77, 175.74, 0) 81%); border-radius: 25px; overflow: hidden">
    <div style="width: 400px; height: 67px; left: 15px; top: 121px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 400px; height: 67px; left: 15px; top: 200px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 400px; height: 67px; left: 15px; top: 278px; position: absolute; background: #D9D9D9"></div>
    <img style="width: 430px; height: 438px; left: 0px; top: 247px; position: absolute; opacity: 0.25; border-top-left-radius: 214.50px; border-top-right-radius: 214.50px; border-bottom-right-radius: 205px; border-bottom-left-radius: 214.50px" src="https://via.placeholder.com/430x438" />
    <div style="width: 366px; height: 135px; left: 32px; top: 121px; position: absolute; text-align: center; color: white; font-size: 50px; font-family: Carter One; font-weight: 400; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE<br/></div>
    <div style="width: 400px; height: 60px; left: 15px; top: 707px; position: absolute; background: #2ABF30; border-radius: 50px"></div>
    <div style="left: 167px; top: 714px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">LOG IN</div>
    <div style="width: 400px; height: 60px; left: 15px; top: 789px; position: absolute; background: #2ABF30; border-radius: 50px"></div>
    <div style="left: 154px; top: 796px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">SIGN UP!</div>
</div>

<div style="width: 100%; height: 100%; position: relative; background: linear-gradient(180deg, #1930AC 50%, rgba(25.77, 49.77, 175.74, 0) 81%); border-radius: 25px; overflow: hidden">
    <div style="width: 400px; height: 60px; left: 15px; top: 350px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="width: 400px; height: 60px; left: 15px; top: 476px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="left: 15px; top: 304px; position: absolute; text-align: center; color: white; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">EMAIL:</div>
    <div style="left: 15px; top: 420px; position: absolute; text-align: center; color: white; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">PASSWORD:</div>
    <div style="left: 96px; top: 546px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Carter One; font-weight: 400; word-wrap: break-word">FORGOT PASSWORD?</div>
    <img style="width: 225px; height: 225px; left: 102px; top: 49px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)" src="https://via.placeholder.com/225x225" />
    <div style="width: 445px; height: 89px; left: -15px; top: 843px; position: absolute; background: #D9D9D9"></div>
</div>

<div style="width: 100%; height: 100%; position: relative; background: linear-gradient(180deg, #1930AC 50%, rgba(25.77, 49.77, 175.74, 0) 81%); border-radius: 25px; overflow: hidden">
    <img style="width: 225px; height: 225px; left: 102px; top: 49px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)" src="https://via.placeholder.com/225x225" />
    <img style="width: 50px; height: 50px; left: 20px; top: 394px; position: absolute" src="https://via.placeholder.com/50x50" />
    <img style="width: 50px; height: 50px; left: 20px; top: 482px; position: absolute" src="https://via.placeholder.com/50x50" />
    <img style="width: 50px; height: 50px; left: 20px; top: 570px; position: absolute" src="https://via.placeholder.com/50x50" />
    <div style="width: 295px; height: 60px; left: 91px; top: 394px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="width: 295px; height: 60px; left: 91px; top: 570px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="width: 295px; height: 60px; left: 91px; top: 482px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="left: 154px; top: 398px; position: absolute; text-align: center; color: white; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">INSTAGRAM</div>
    <div style="left: 176px; top: 486px; position: absolute; text-align: center; color: white; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">GOOGLE</div>
    <div style="left: 157px; top: 570px; position: absolute; text-align: center; color: white; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">FACEBOOK</div>
    <div style="width: 445px; height: 89px; left: 0px; top: 843px; position: absolute; background: #D9D9D9"></div>
</div>

<div style="width: 100%; height: 100%; position: relative; background: linear-gradient(180deg, #1930AC 0%, rgba(61.29, 65.92, 177.21, 0) 100%); border-radius: 25px; overflow: hidden">
    <div style="width: 100px; height: 60px; left: 153px; top: 349px; position: absolute; background: black; border-radius: 25px"></div>
    <img style="width: 225px; height: 225px; left: 90px; top: 49px; position: absolute" src="https://via.placeholder.com/225x225" />
    <div style="width: 446px; height: 88px; left: 0px; top: 844px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 159px; top: 356px; position: absolute; text-align: center; color: white; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">DEPT:</div>
    <div style="width: 400px; height: 60px; left: 15px; top: 436px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="width: 400px; height: 60px; left: 15px; top: 709px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="left: 134px; top: 716px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">CSE-CYSC</div>
    <div style="width: 400px; height: 60px; left: 15px; top: 529px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="width: 400px; height: 60px; left: 15px; top: 619px; position: absolute; background: linear-gradient(180deg, #D9D9D9 0%, rgba(217, 217, 217, 0) 100%); border-radius: 25px"></div>
    <div style="left: 160px; top: 443px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">AI-ML</div>
    <div style="left: 143px; top: 622px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">CSE-IOT</div>
    <div style="left: 163px; top: 536px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Carter One; font-weight: 400; word-wrap: break-word">AI-DS</div>
</div>
```
CSS:
```
// SAVEETHA ENGINEERING COLLEGE<br/>
color: white;
 font-size: 50px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// LOG IN
color: black;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// SIGN UP!
color: black;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word

// EMAIL:
color: white;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// PASSWORD:
color: white;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// FORGOT PASSWORD?
color: white;
 font-size: 20px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word

// INSTAGRAM
color: white;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// GOOGLE
color: white;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// FACEBOOK
color: white;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word

// DEPT:
color: white;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// CSE-CYSC
color: black;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// AI-ML
color: black;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// CSE-IOT
color: black;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
---
// AI-DS
color: black;
 font-size: 30px;
 font-family: Carter One;
 font-weight: 400;
 word-wrap: break-word
```
## OUTPUT:
![Screenshot (132)](https://github.com/NavinkumarJ/Figma/assets/115530758/8cb06b25-9cb3-4012-8d02-80bd04319ec0)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
