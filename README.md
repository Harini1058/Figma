# Ex09 Event Registration Web Application
## Date:08.10.2025

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
```
Home page
import React from "react";
import logo from "./logo.png";
import rectangle111141357 from "./rectangle-111141357.svg";
import rectangle111141358 from "./rectangle-111141358.svg";
import saveetha1 from "./saveetha-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const Iphone = () => {
  return (
    <div className="bg-[#f6dcdc] overflow-hidden w-full min-w-[393px] min-h-[852px] relative">
      <img
        className="absolute top-[74px] left-[3px] w-[390px] h-[71px] aspect-[5.54] object-cover"
        alt="Logo"
        src={logo}
      />

      <img
        className="absolute top-[173px] left-14 w-72 h-72 aspect-[1] object-cover"
        alt="Saveetha"
        src={saveetha1}
      />

      <div className="absolute top-[655px] left-[103px] w-[188px] h-[43px] bg-[#5f32a6]" />

      <div className="absolute top-[663px] left-[149px] h-7 flex items-center justify-center [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        REGISTER
      </div>

      <img
        className="absolute top-[1276px] left-[-1624px] w-[219px] h-8"
        alt="Rectangle"
        src={rectangle111141357}
      />

      <img
        className="absolute top-[784px] left-[-2049px] w-[182px] h-[35px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <img
        className="absolute top-[699px] left-[180px] w-3.5 h-[70px]"
        alt="Rectangle"
        src={rectangle111141358}
      />

      <div className="absolute top-[582px] left-[106px] w-[182px] h-[45px] bg-[#342afe]" />

      <div className="absolute top-[591px] left-[163px] h-7 flex items-center justify-center [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        LOGIN
      </div>

      <div className="absolute top-[469px] left-[43px] w-[274px] h-7 flex items-center justify-center [font-family:'Inter-SemiBold',Helvetica] font-semibold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SINGING&nbsp;&nbsp;COMPETITION
      </div>
    </div>
  );
};
Events page
import React from "react";
import SING1 from "./SING-1.png";

export const Iphone = () => {
  return (
    <div className="bg-[#a74d4d] w-full min-w-[393px] min-h-[852px] flex flex-col">
      <img
        className="ml-[45px] w-[304px] h-[232px] mt-[88px] aspect-[1.31] object-cover"
        alt="Sing"
        src={SING1}
      />

      <div className="flex items-center justify-center ml-[143px] w-[146px] h-7 mt-[57px] [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px]">
        EVENTS
      </div>

      <div className="flex items-center justify-center ml-[71px] w-[150px] h-7 mt-[43px] [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px]">
        1.Solo singing
      </div>

      <div className="flex items-center justify-center ml-[71px] w-[158px] h-[29px] mt-[17px] [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        2.Group singing
      </div>

      <div className="flex items-center justify-center ml-[71px] w-[135px] h-[45px] mt-4 [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px]">
        3.Folk song
      </div>

      <div className="flex items-center justify-center ml-[71px] w-[121px] h-7 mt-[18px] [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px]">
        4.Rap song
      </div>

      <div className="flex items-center justify-center ml-[71px] w-[181px] h-7 mt-[25px] [font-family:'Inter-SemiBold',Helvetica] font-semibold text-white text-xl tracking-[-0.40px] leading-[28.0px]">
        5.Devotional song
      </div>
    </div>
  );
};
Registration page
import React from "react";
import image from "./image.svg";
import rectangle111141371 from "./rectangle-111141371.svg";
import sings1 from "./sings-1.png";
import textOnAPath2 from "./text-on-a-path-2.svg";
import textOnAPath3 from "./text-on-a-path-3.svg";
import textOnAPath from "./text-on-a-path.svg";

export const Iphone = () => {
  return (
    <div className="bg-[#ff5050] overflow-hidden w-full min-w-[389px] min-h-[843px] relative">
      <img
        className="absolute top-[631px] left-[15px] w-[339px] h-[203px] aspect-[1.67] object-cover"
        alt="Sings"
        src={sings1}
      />

      <div className="absolute top-[38px] left-[42px] w-[298px] h-[47px] flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-white text-xl tracking-[-0.40px] leading-[28.0px]">
        EVENT&nbsp;&nbsp;REGISTRATION&nbsp;&nbsp;FORM
      </div>

      <img
        className="absolute top-56 left-[-2965px] w-[236px] h-[39px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <div className="absolute top-[105px] left-[59px] w-[236px] h-[47px] bg-[#d9d9d9]" />

      <div className="absolute top-[110px] left-[140px] w-[102px] h-[37px] flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        Name:
      </div>

      <img
        className="absolute top-[283px] left-[-2960px] w-[231px] h-14"
        alt="Text on a path"
        src={image}
      />

      <div className="absolute top-44 left-[130px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        Gender
      </div>

      <div className="absolute top-[246px] left-[146px] w-[39px] h-11 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        Age
      </div>

      <div className="absolute top-[290px] left-[57px] w-[238px] h-[54px] bg-[#d9d9d9]" />

      <div className="absolute top-[303px] left-[114px] w-[139px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        Department:
      </div>

      <div className="absolute top-[359px] left-[57px] w-[235px] h-14 bg-[#d9d9d9]" />

      <div className="absolute top-[379px] left-[116px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        Email ID:
      </div>

      <div className="absolute top-[480px] left-16 w-[13px] h-[3px] bg-[#d9d9d9]" />

      <div className="absolute top-[430px] left-[57px] w-[238px] h-[58px] bg-[#d9d9d9]" />

      <div className="absolute top-[503px] left-[57px] w-[238px] h-[53px] bg-[#d9d9d9]" />

      <div className="absolute top-[517px] left-[87px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        Events To Register:
      </div>

      <div className="absolute top-[162px] left-[59px] w-[236px] h-14 bg-[#d9d9d9]" />

      <div className="absolute top-[182px] left-[133px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        Gender:
      </div>

      <img
        className="absolute top-[1196px] left-[-2044px] w-[100px] h-[100px]"
        alt="Rectangle"
        src={rectangle111141371}
      />

      <div className="absolute top-[228px] left-[59px] w-[236px] h-12 bg-[#d9d9d9]" />

      <div className="absolute top-[239px] left-[133px] w-[89px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        Age:
      </div>

      <div className="absolute top-[451px] left-[97px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-black text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        Mobile Number:
      </div>

      <img
        className="absolute top-[696px] left-[-2960px] w-[228px] h-[45px]"
        alt="Text on a path"
        src={textOnAPath2}
      />

      <img
        className="absolute top-[696px] left-[-2968px] w-[236px] h-10"
        alt="Text on a path"
        src={textOnAPath3}
      />

      <div className="absolute top-[565px] left-16 w-[231px] h-[55px] bg-[#33adf9]" />

      <div className="absolute top-[580px] left-[124px] h-7 flex items-center justify-center [font-family:'Inter-Bold',Helvetica] font-bold text-white text-xl tracking-[-0.40px] leading-[28.0px] whitespace-nowrap">
        REGISTER
      </div>
    </div>
  );
};
Thank you page
import React from "react";
import WIN1 from "./WIN-1.png";
import WIN2 from "./WIN-2.png";
import logo1 from "./logo-1.png";

export const Iphone = () => {
  return (
    <div className="bg-[#6bfc3b] overflow-hidden w-full min-w-[393px] min-h-[852px] flex flex-col">
      <img
        className="ml-[-3353.8px] w-[15.84px] h-[8.89px] mt-[2.2px] aspect-[1.78] object-cover"
        alt="Win"
        src={WIN1}
      />

      <img
        className="ml-[19px] w-[359px] h-[75px] mt-[38.9px] aspect-[4.79] object-cover"
        alt="Logo"
        src={logo1}
      />

      <img
        className="ml-[19px] w-[355px] h-[199px] mt-[25px] aspect-[1.78] object-cover"
        alt="Win"
        src={WIN2}
      />

      <div className="flex items-center justify-center ml-12 w-[317px] h-7 mt-14 [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        ITS&nbsp;&nbsp;THE&nbsp;&nbsp;TIME&nbsp;&nbsp;TO&nbsp;&nbsp;SHOWCASE
      </div>

      <div className="flex items-center justify-center ml-[107px] w-[156px] h-[47px] mt-[25px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-black text-xl tracking-[-0.40px] leading-[28.0px]">
        YOUR&nbsp;&nbsp;TALENTS
      </div>

      <div className="ml-[99px] w-[228px] h-[38px] mt-[55px] [font-family:'Inter-Bold',Helvetica] font-bold text-black text-2xl tracking-[0] leading-[normal]">
        ALL&nbsp;&nbsp;THE&nbsp;&nbsp;BEST
      </div>

      <div className="ml-[72px] w-[249px] h-11 mt-[60px] [font-family:'Inter-Bold',Helvetica] font-bold text-black text-4xl tracking-[0] leading-[normal]">
        THANK&nbsp;&nbsp;YOU!!
      </div>
    </div>
  );
};
```

## OUTPUT:
![alt text](<Screenshot 2025-10-08 094149.png>)

![alt text](<Screenshot 2025-10-08 094235.png>)

![alt text](<Screenshot 2025-10-08 094302.png>)

![alt text](<Screenshot 2025-10-08 094329.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
