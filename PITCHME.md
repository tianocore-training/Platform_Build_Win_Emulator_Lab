---?image=assets/images/gitpitch-audience.jpg
@title[Platform Build Win Emulator Lab]
<br><br>
<br><br><br>
## <span class="gold"   >UEFI & EDK II Training</span>

<span style="font-size:0.95em" > Platform Build Windows Emulator Lab </span>

<br>
<span style="font-size:0.75em" ><a href='http://www.tianocore.org'>tianocore.org</a></span>
Note:
  PITCHME.md for UEFI / EDK II Training  Platform Build Win Lab

  Copyright (c) 2018, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.



---  
@title[Lesson Objective]

### <p align="center"<span class="gold"   >Platform Build Labs </span></p>
<br>
<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-magenta]<span style="font-size:0.9em">&nbsp;&nbsp;Pin Visual Studio Command Prompt to Windows <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Task Bar  </span><br><br>
 @fa[certificate gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;Build a EDK II Platform using Emulator package </span><br><br>
 @fa[certificate gp-bullet-cyan]<span style="font-size:0.9em">&nbsp;&nbsp;Run the Emulator in Windows  </span><br><br>
   


---?image=assets/images/binary-strings-black2.jpg
@title[Pin VS CMD Prompt Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pin VS Command Prompt </span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pin the Visual Studio Command prompt to Windows <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Task Bar</span>


---?image=/assets/images/slides/Slide4.JPG
@title[Pin VS CMD Prompt]
### <p align="right"><span class="gold" >Pin  VS Command Prompt</span></p>

@snap[north-east span-25 ]
<br>
<br>
<p style="line-height:40%" align="center">@fa[windows gp-bullet-cyan]<BR><span style="font-size:0.450em;  " >Windows 10 </span></p>
<br>
@snapend

@snap[north-east span-60 ]
<br>
<br>
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >Steps to Pin Visual Studio Command Prompt to task bar for Windows 10 </span></p>
<ol style="line-height:0.8;">
 <li><span style="font-size:0.80em;  " >Using the Start menu in Windows 10, Left Click on "Windows Key" Lower Left @fa[windows gp-bullet-cyan]</span></li>
 <li><span style="font-size:0.80em;  " >Scroll down from the scroll bar on the right until "Visual Studio 201@color[#e49436](<i>n</i>)" </span></li>
 <li><span style="font-size:0.80em;  " >Left Click "Visual Studio 201@color[#e49436](<i>n</i>)"</span></li>
</ol>
<br>
@snapend


Note:



---?image=/assets/images/slides/Slide5.JPG
@title[Pin VS CMD Prompt 02]
### <p align="right"><span class="gold" >Pin  VS Command Prompt</span></p>
@snap[north-east span-60 ]
<br>
<br>
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >4. Left Click <b>"Visual Studio Tools"</b> </span></p>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >This will open another Windows file explorer window <br></span><span style="font-size:0.60em;  " > Note: <i>VS 2013 example, other version of VS maybe different</i>  </span></p>

<br>
@snapend


Note:



---?image=/assets/images/slides/Slide6.JPG
@title[Pin VS CMD Prompt 03]
### <p align="right"><span class="gold" >Pin  VS Command Prompt</span></p>
@snap[north-east span-50 ]
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >5. Select <b>"Developer Command Prompt for VS201<i>n</i>"</b> </span></p>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >6. Right Click to open Windows dialog box </span></p>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " ><font color="yellow">Do not use any of the other<br> ".. Command Prompts" </font></span></p>

<br>
@snapend
Note:



---?image=/assets/images/slides/Slide7.JPG
@title[Pin VS CMD Prompt 04]
### <p align="right"><span class="gold" >Pin  VS Command Prompt</span></p>

@snap[north-east span-40 ]
<br>
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >7. Left Click  on <br>&nbsp;&nbsp;&nbsp;"Pin to to taskbar" </span></p>
<br>
@snapend


Note:



---?image=/assets/images/slides/Slide8.JPG
@title[Pin VS CMD Prompt 05]
### <p align="right"><span class="gold" >Pin  VS Command Prompt</span></p>

@snap[north-east span-50 ]
<br>
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;" >8. Open the VS Command Prompt </span></p>
<br>
<p style="line-height:60%" align="left"><span style="font-size:0.65em; ">&nbsp;  All Windows Labs use this short-cut to Build Edk II platforms and projects using Windows Visual Studio<br>
@size[.75em](2010 / 2012 / 2013 / 2015 or 2017)</span></p>
@snapend
Note:



---?image=assets/images/binary-strings-black2.jpg
@title[End of Pin VS Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;End Pin  VS Prompt</span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>



---?image=assets/images/binary-strings-black2.jpg
@title[Lab 1 -Build OVMF Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Build Emulator</span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Setup EmulatorPkg to build and run emulation <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;w/ Windows</span>



---
@title[Optional - Downloading the Edk II Source]
<p align="right"><span class="gold" ><b>Download the Edk II Source&nbsp;&nbsp;<i>- Optional</i></b></span></p>


<span style="font-size:0.9em" ><i>OPTIONAL</i> - Open a  “git” command prompt and create a source working directory</span>
```
 C:\> mkdir WS
 C:\> cd WS
```

<span style="font-size:0.8em" >OPTIONAL - Internet Proxies – (company Firewall used for example)</span>

```
 C:\WS> git config --global https.proxy <proxyname>.domain.com:<port>
 C:\WS> git config --global http.proxy <proxyname>.domain.com:<port>
```

<span style="font-size:0.8em" >OPTIONAL - Download edk2 source tree using Git command prompt</span>

```
  C:\WS> git clone --recursive  https://github.com/tianocore/edk2.git
  C:\WS> git clone  https://github.com/tianocore/edk2-libc.git
 

```

<span style="font-size:0.7em" ><b>@color[yellow](NOTE:)</b> Lab Material will have a different “edk2” </span>


Note:

OPTIONAL - Open a  “git” command prompt and create a source working directory
<pre>
- C:\> mkdir WS
- C:\> cd WS

- OPTIONAL - Internet Proxies – (company Firewall used for example)

- C:\WS> git config --global https.proxy <proxyname>.domain.com:<port>
- C:\WS> git config --global http.proxy <proxyname>.domain.com:<port>

- OPTIONAL - Download edk2 source tree using Git command prompt
- C:\WS> git clone https://github.com/tianocore/edk2.git

</pre>

- NOTE: Lab Material will have a different “edk2”


---?image=assets/images/binary-strings-black2.jpg
@title[Setup Lab Material sub Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Setup Lab Material </span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Lab_Material_FW.zip</span>

---
@title[Download Lab_Material_FW -getting the Source ]
### <p align="right"><span class="gold" >Download Lab Material</span><br></span></p>
<span style="font-size:0.9em" >Download the Lab_Material_FW.zip from : </span> @fa[github gp-bullet-white] <span style="font-size:0.7em"><a href="https://github.com/tianocore-training/Lab_Material_FW/archive/master.zip">github.com Lab_Matrial_FW.zip</a></span><br>
<br>
<span style="font-size:0.9em" >OR<br>Use `git clone` to download the Lab_Material_FW<span>
```bash
C:\> git clone https://github.com/tianocore-training/Lab_Material_FW.git
```
<span style="font-size:0.9em" >Directory Lab_Material_FW will be created</span>
```
   FW 
    - Documentation 
	- DriverWizard 
	- edk2-ws      
	- edk2Linux 
	- LabSampleCode 
	- Nasm
	
```

Note:

---?image=/assets/images/slides/Slide14.JPG
@title[Build  Edk2 -getting the Source ]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" >– Extract the Source  </span></p>

@snap[north-west span-100 ]
<br>
<br>
<br>
<p style="line-height:70%" align="left"><span style="font-size:0.75em;  " >1. Extract the Downloaded <font face="Consolas">Lab_Material_FW-master.zip to C:\ </font> </span></p>
<br>
@snapend



Note:
Extract the Downloaded Lab_Material_FW.zip to Home (this will create a directory FW )

---?image=/assets/images/slides/Slide15.JPG
@title[Build  Edk2 -getting the Source 02]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" > - Copy edk2-ws </span></p>

@snap[north-west span-100 ]
<br>
<p style="line-height:70%" align="left" ><span style="font-size:0.7em;" >2. Open a VS command prompt <br><br> 3. 
Create a working space directory "FW" <br>
<span style="background-color: #000000"><font face="Consolas">@size[.7em](&nbsp;&nbsp; C:&bsol;&gt; mkdir FW &nbsp;&nbsp;&nbsp;&nbsp;) </font></span>
<br><br>4. From the downloaded Lab_Material_FW folder, <b>copy</b> and <b>paste</b> folder <font face="Consolas">"..\edk2-ws" to "C:/FW"</font>
</span></p>

@snapend



Note:
- Open a VS Command prompt   
- Create a working  space directory “FW”
  -   C:\> mkdir FW

- From the downloaded Lab_Material_FW folder, copy and 
   -  paste folder “..\edk2-ws” to C:/FW


---?image=/assets/images/slides/Slide16.JPG
@title[Build  Edk2 -get Nasm]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" > - Get Nasm </span></p>

@snap[north-west span-70 ]
<br>
<br>
<p style="line-height:70%" align="left" ><span style="font-size:0.7em;" >5.&nbsp;
Copy<font face="Consolas"> Nasm </font> directory to <font face="Consolas">C:&bsol;</font><br>
@size[.8em](&lpar;creating <font face="Consolas">C:&bsol;Nasm</font> directory&rpar;)
</span></p>

@snapend

Note:

Copy Nasm directory to C:\
(creating C:\Nasm directory)


---
@title[Build  Edk2 -install Python]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" > – Download and install Python </span></p>


@snap[north-west span-60 ]
<br>
<br>
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.80em;  " >
 Download and install Python 3.7.x for Windows from: <br> https://www.python.org
<br>
<br>
</span></p>

<br>
@snapend

@snap[north-east span-45 ]
<br>
<br>
<br>
<br>
<br>
<a href="https://www.python.org">
![python_logo](assets/images/python-logo@2x.png)</a>

@snapend




Note:

---
@title[Build  Edk2 -build BaseTools]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" > – build <font face="Consolas">BaseTools</font></span></p>

@snap[north-west span-100 ]
<br>
<br>
<p style="line-height:60%" align="left" ><span style="font-size:0.7em;" >
Open VS Command prompt and Cd to work space directory <br>
<span style="background-color: #000000"><font face="Consolas">
@size[.7em](&nbsp;&nbsp;cd  C:&bsol;&gt;FW\edk2-ws &nbsp;&nbsp;&nbsp;&nbsp;) </font></span> <br>
<br>
Setup the local environment: (see batch file setenv.bat )<br>
<span style="background-color: #000000"><font face="Consolas">
@size[.7em](&nbsp;&nbsp;$&gt; set WORKSPACE=%CD% &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <br>)
@size[.7em](&nbsp;&nbsp;$&gt; set PACKAGES_PATH=%WORKSPACE%\edk2;%WORKSPACE%\edk2-libc  &nbsp;&nbsp;  )</font></span> <br>
<br>
Invoke Edksetup.bat from directory <font face="Consolas">C:/FW/edk2-ws/edk2</font> to Build <font face="Consolas">BaseTools </font><br>
<span style="background-color: #000000"><font face="Consolas">
@size[.7em](&nbsp;&nbsp;$&gt; cd edk2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>)
@size[.7em](&nbsp;&nbsp;$&gt; edksetup.bat Rebuild&nbsp;&nbsp;&nbsp;&nbsp;)</font></span> <br>
</span></p>
<br>
@snapend

@snap[south-west span-100 ]
<p style="line-height:45%" align="left" ><span style="font-size:0.5em;" >
Building BaseTools only needs to be done once but setting up local environment and edksetup.bat needs to be done each new VS prompt session
</span></p>
@snapend




@snap[east span-40 fragment ]
<br>
<br>
<br>
<br>
<p style="line-height:40%" align="left"><span style="font-size:02.80em;  " ><br><br>
@color[yellow](&#8678;)
</span></p>
@snapend



---?image=assets/images/binary-strings-black2.jpg
@title[Build  sub Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Build EmulatorPkg </span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>


---?image=/assets/images/slides/Slide20.JPG
@title[Build Edk2 -update target.txt]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" > – Update <font face="Consolas">Target.txt</font></span></p>

@snap[north-west span-70 ]
<br>
<p style="line-height:60%" align="left" ><span style="font-size:0.7em;" >
@size[1.1em](<b>EmulatorPkg</b>) - Build with edk2  <br><br>
Invoke <font face="Consolas">Edksetup.bat </font>
</span></p>
<p style="line-height:45%" align="left" ><span style="font-size:0.5em; font-family:Consolas;">
<span style="background-color: #000000">
&nbsp;&nbsp;$&gt; cd C:\FW\edk2-ws\edk2 &nbsp;&nbsp;   <br>
&nbsp;&nbsp;$&gt; edksetup.bat &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <br>
</span>
</span></p>

<p style="line-height:50%" align="left" ><span style="font-size:0.7em;" ><br>
<b>Edit</b> the file <font face="Consolas">Conf/target.txt</font> @size[.7em](&lpar;change TOOL_CHAIN_TAG&rpar;<br>)
<font face="Consolas">@size[.7em](&nbsp; notepad Conf/target.txt )</font>
</span></p>

@snapend

@snap[north-west span-60 ]
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p style="line-height:34%" align="left" ><span style="font-size:0.35em; font-family:Consolas;">
<font color="black"><br><br>
&nbsp;&nbsp;TARGET_ARCH&nbsp;&nbsp;&nbsp;&nbsp;           = X64 <br>
&nbsp;&nbsp; &nbsp;&nbsp;. &nbsp;&nbsp;. &nbsp;&nbsp;. <br>
&nbsp;&nbsp;TOOL_CHAIN_TAG &nbsp;       = VS2015x86 <br>
</font>
</span></p>
@snapend


@snap[south-west span-100 ]
<p style="line-height:50%" align="left" ><span style="font-size:0.75em;" >
@size[.8em](<b>Save</b> and <b>Exit</b>)<br>
<br>
<br>
<b>Build Emulator</b>
</span></p>
<p style="line-height:50%" align="left" ><span style="font-size:0.5em; font-family:Consolas;">
<span style="background-color: #000000">
&nbsp;&nbsp;$&gt; build –D ADD_SHELL_STRING –D WIN_SEC_BUILD -a X64 &nbsp;&nbsp;   <br>
</span>
</span></p>
@snapend


@snap[south-east span-30 fragment ]
<p style="line-height:10%" align="left"><span style="font-size:02.80em;  " ><br><br>
@color[yellow](&#8678;)
</span></p>
@snapend




Note:

-  Cd C:/fw/edk2-ws/edk2

- invoke edksetup.bat 
- change MYTOOLS to VS2015x86 or whatever
- edit Conf/target.txt
  -  TARGET_ARCH           = X64
  -	. . .
  -  TOOL_CHAIN_TAG        = VS2015x86

-  build –D ADD_SHELL_STRING –D WIN_SEC_BUILD -a X64


---
@title[Possible Build Errors]
<p align="right"><span class="gold" >@size[1.1em](<b>Possible Build Errors </b>)</span><span style="font-size:0.75em;" ></span></p>

<p style="line-height:80%"><span style="font-size:0.8em" >1. If you get a BUILD Error:  Error “<font face="Consolas">C:/Program </font>“ not found</span></p>
<ul style="line-height:0.8;">
  <li><span style="font-size:0.7em" >First check that you have opened Visual Studio and installed the “C++”   </span> </li>
  <li><span style="font-size:0.7em" >Open Visual Studio and create a “C++” project </span> </li>
  <li><span style="font-size:0.7em" > (This will take some time to install)</span> </li>
</ul>  
<p style="line-height:80%"><span style="font-size:0.8em" >2. If you get a BUILD Error: Check if  RC.Exe compiler not found is the error -<a href="https://gitpitch.com/tianocore-training/Platform_Build_Win_Emulator_Lab/master#/31" > here</a> </span> </p>
<p style="line-height:80%"><span style="font-size:0.8em" >3. If you get a BUILD Error: <font face="Consolas">fatal error C1041: cannot open program database</font> … Check 
<a href="https://gitpitch.com/tianocore-training/Platform_Build_Win_Emulator_Lab/master#/32"> here</a>  </span> </p>


Note:



---?image=/assets/images/slides/Slide22.JPG
@title[Build Edk2 -build inside VS Prompt]
<p align="right"><span class="gold" >@size[1.1em](<b>Build EDK II  </b>)</span><br>
<span style="font-size:0.75em;" > – Inside VS Prompt</span></p>


@snap[south-east span-40  ]
<p style="line-height:50%" align="right"><span style="font-size:0.8em" >
Finished build
<br>
<br>
<br>
<br>
<br>
<br>
</span></p>
@snapend

Note:
- 


---?image=/assets/images/slides/Slide23.JPG
@title[Build Edk2 -invoke emulator]
<p align="right"><span class="gold" >@size[1.1em](<b>Invoke Emulation  </b>)</span><span style="font-size:0.75em;" ></span></p>

@snap[north-west span-45 ]
<br>
<br>
<p style="line-height:65%" align="left"><span style="font-size:0.75em" >From the command prompt<br><br></span>
&nbsp;&nbsp;<font face="Consolas"><span style="background-color: #000000; font-size:0.55em; ">
&nbsp;&nbsp;$&gt;  RunEmulator.bat &nbsp;&nbsp;</span></font>
<br>
<br>
<span style="font-size:0.75em" >
OR<br>
run <font face="Consolas">@color[yellow](WinHost.exe) </font> from:<br>&nbsp;&nbsp;
<font face="Consolas">@size[.7em](Build/ . . ./X64 directory)</font>
</span></p>
<br>
<p style="line-height:50%" align="left"><span style="font-size:0.5em" > Notice 2 "GOP Window n" opened </span></p>
@snapend



Note:

---?image=/assets/images/slides/Slide24.JPG
@title[Build Edk2 -exit emulator]
<p align="right"><span class="gold" >@size[1.1em](<b>Emulator at Shell Prompt  </b>)</span><span style="font-size:0.75em;" ></span></p>

@snap[north-west span-45 ]
<br>
<br>
<br>
<p style="line-height:80%" align="left"><span style="font-size:0.8em" >Type: "Reset" to exit<br><br>
</span></p>
@snapend

Note:


---  
@title[Summary]
##### <p align="center"<span class="gold"   >Summary </span></p><br>

 @fa[certificate gp-bullet-magenta]<span style="font-size:0.9em">&nbsp;&nbsp;Pin Visual Studio Command Prompt to Windows <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Task Bar  </span><br><br>
 @fa[certificate gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;Build a EDK II Platform using Emulator package </span><br><br>
 @fa[certificate gp-bullet-cyan]<span style="font-size:0.9em">&nbsp;&nbsp;Run the Emulator in Windows  </span><br><br>
 

---?image=assets/images/gitpitch-audience.jpg
@title[Questions]
<br>
![Questions](/assets/images/questions.JPG =10x) 

---
@title[return to main]
<p align="center"><span class="gold"   >@size[1.2em](<b>Return to Main Training Page</b>)</span></p>
<br>
<br>
<br>
<br>
<br>
<p align="center"><span style="font-size:0.9em">Return to Training Table of contents for next presentation <a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki#schedule--outline">link</a></span></p>

@snap[north span-30 ]
<br>
<br>
<br>
<a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki#schedule--outline">
![trainingLogo](/assets/images/returnTrainingLogo.png)</a>
@snapend

---?image=assets/images/gitpitch-audience.jpg
@title[Logo Slide]
<br><br><br>
![Logo Slide](/assets/images/TianocoreLogo.png =10x)


---
@title[Acknowledgements]
#### <p align="center"><span class="gold"   >Acknowledgements</span></p>

```c++
/**
Redistribution and use in source (original document form) and 'compiled' forms (converted
to PDF, epub, HTML and other formats) with or without modification, are permitted provided
that the following conditions are met:

Redistributions of source code (original document form) must retain the above copyright 
notice, this list of conditions and the following disclaimer as the first lines of this 
file unmodified.

Redistributions in compiled form (transformed to other DTDs, converted to PDF, epub, HTML
and other formats) must reproduce the above copyright notice, this list of conditions and 
the following disclaimer in the documentation and/or other materials provided with the 
distribution.

THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR IMPLIED 
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND 
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL TIANOCORE PROJECT BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, 
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, 
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF ADVISED OF THE POSSIBILITY 
OF SUCH DAMAGE.

Copyright (c) 2019, Intel Corporation. All rights reserved.
**/

```


---?image=assets/images/binary-strings-black2.jpg
@title[Backup Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Back up</span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>

---  
@title[Build Errors]
<br>
<br>
<br>
<br>
##### <p align="center"<span class="gold"   >Build Errors</span></p><br>


---
@title[Build Error- RC.exe ]
<p align="right"><span class="gold" ><b>Build Error- RC.exe </b></span></p>
<p style="line-height:90%"><span style="font-size:0.9em" >Because RC.Exe is not found, Error Message:</span></p>

```
   "c:\Program Files (x86)\Windows Kits\8.0\bin\x64\rc.exe" 
/Foc:\edkii.svn\Build\NT32IA32\DEBUG_VS2013x86\IA32\MdeModulePkg\Application\HelloWorld\HelloWorld\OUTPUT
\HelloWorldhii.lib 
c:\edkii.svn\Build\NT32IA32\DEBUG_VS2013x86\IA32\MdeModulePkg\Application\HelloWorld\HelloWorld\OUTPUT\He
lloWorldhii.rc
'c:\Program' is not recognized as an internal or external command,
operable program or batch file.
 
NMAKE : fatal error U1077: '"c:\Program Files (x86)\Windows Kits\8.0\bin\x64\rc.exe' : return code '0x1'
Stop.

```

<p style="line-height:90%"><span style="font-size:0.9em" >Find where the RC.EXE is located on your VS Installation:  </span></p>

<p style="line-height:90%"><span style="font-size:0.9em" >Example (VS 2013):  The RC.exe is located on this machine: <br>
<span style="font-size:0.5em" >`C:\Program Files (x86)\Windows Kits\8.1\bin\x64` </span></span></p>
<span style="font-size:0.9em" >Edit `Conf/tools_def.txt` </span>

Note:


+++
@title[Build Error- RC.exe 02]
<p align="right"><span class="gold" ><b>Build Error- RC.exe Cont...</b></span></p>

<span style="font-size:0.9em" >Edit `Conf/tools_def.txt` </span><br>
<p style="line-height:90%"><span style="font-size:0.9em" >Search for your installation of Visual Studio (2013 or 2015)</span></p>
<p style="line-height:90%"><span style="font-size:0.9em" >Update according to the path for where the RC.EXE is found </span></p>

```
# Microsoft Visual Studio 2013 Professional Edition
DEFINE WINSDK8_BIN       = c:\Program Files\Windows Kits\8.1\bin\x86\
DEFINE WINSDK8x86_BIN    = c:\Program Files (x86)\Windows Kits\8.1\bin\x64
 
# Microsoft Visual Studio 2015 Professional Edition
DEFINE WINSDK81_BIN       = c:\Program Files\Windows Kits\8.1\bin\x86\
DEFINE WINSDK81x86_BIN    = c:\Program Files (x86)\Windows Kits\8.1\bin\x64

```


Note:
---
@title[Build Error- C1041 ]
<p align="right"><span class="gold" ><b>Build Error: fatal error C1041: </b></span></p>
<p style="line-height:90%"><span style="font-size:0.9em" >Build Error from fatal error C1041: cannot open program database</span></p>

<p style="line-height:90%"><span style="font-size:0.9em" >This Error is usually because the location you are building is being shared by another application in Windows.  Example: Syncplicity may cause this</span></p>

<span style="font-size:0.9em" >Error Message:</span>

```
k:\fw\edk2\MdePkg\Library\BaseLib\LinkedList.c : fatal error C1041: cannot open program 
database 
'k:\fw\edk2\build\nt32ia32\debug_vs2013x86\ia32\mdepkg\library\baselib\baselib\vc120.pdb'; if 
multiple CL.EXE write to the same .PDB file, please use /FS
NMAKE : fatal error U1077: '"C:\Program Files (x86)\Microsoft Visual Studio 
12.0\Vc\bin\cl.exe"' : return code '0x2'
Stop.

```

<p style="line-height:90%"><span style="font-size:0.9em" ><b>Solution:</b>  Try using a Workspace that is not shared
</span></p>

