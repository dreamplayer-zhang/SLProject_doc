SLProject                         {#mainpage}
============

<p>
Welcome to the SLProject. SL stands for Scene Library. It is developed at the 
<a href="http://www.bfh.ch/en/studies/bachelor/engineering_and_information_technology/information_technology.html">
Berne University of Applied Sciences (BFH)</a> and is used for student projects in the 
<a href="https://www.cpvrlab.ti.bfh.ch/">cpvrLab</a>. 
The various applications show what you can learn in one semester about 3D computer 
graphics in real time rendering and ray tracing. The framework is built in C++ and 
OpenGL ES 2.0 and runs without changes on Windows, Linux, Mac OSX, Android and Apple iOS. 
The framework can render alternatively with Ray Tracing and Path Tracing which provides 
in addition high quality transparencies, reflections and soft shadows. You can find the 
demo app also on the <a href="https://play.google.com/store/apps/details?id=ch.fhnw.comgr&amp;feature=search_result#?t=W251bGwsMSwyLDEsImNoLmZobncuY29tZ3IiXQ">Android Market</a>.
</p>

<p>
The SLProject is hosted online on <a href="https://github.com/cpvrlab/SLProject">GitHub</a>.
</p>
<p>
The source code is provided under the <a href="http://www.gnu.org/licenses/gpl.html">GNU General Puplic License (GPL)</a>. 
The code is provided without any warranties whether expressed or implied.
</p>

<h3>Read the following wiki page for more information:</h3>
<ul>
<li><a href="http://cpvrlab.github.io/SLProject/">SLProject Homepage</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/SLProject-Features">SLProject Features</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Build-with-VisualStudio">Build instructions with MS Visual Studio</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Build-with-QtCreator">Build instructions with QtCreator under Windows, OSX or Linux.</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Build-for-Android">Build instructions for the Android build with Visual Studio</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Build-for-Apple-iOS">Build instructions for the iOS build with Apple XCode</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Build-minimal-OpenGL-apps">Minimal OpenGL Applications in C++, C#, Java and WebGL</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Folder-Structure">Repository folder structure</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Coding-Style-Guidelines">Coding Style Guidelines for Contributors</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Generate-the-Documentation">How to generate the HTML Documentation using Doxygen</a></li>
<li><a href="http://cpvrlab.github.io/SLProject/html/index.html">Online HTML Documentation</a></li>
<li><a href="https://github.com/cpvrlab/SLProject/wiki/Version-History">Version History</a></li>
</ul>

<h3>Introduction:</h3>
<p>
Read the <a href="md__introduction.html"><b>Introduction Page</b></a> for an overview of the framework.<br>
Read the <a href="md_on_paint.html"><b>onPaint Page</b></a> for an overview how on frame gets rendered.
</p>

<h3>Framework Dependencies:</h3>
The framework uses beside OpenGL the following exteral libraries that are also included in the SLProject repository:
<ul>
    <li><a href="http://www.ijg.org/">JPEG</a> for JPEG image type loading.</li>
    <li><a href="http://www.libpng.org/pub/png/libpng.html">PNG image type loading.</a></li>
    <li><a href="http://zlib.net/">ZLIB</a> for compression of PNG images.</li>
    <li><a href="http://nvwa.sourceforge.net/">nvwa</a> for memory management.</li>
    <li><a href="http://assimp.sourceforge.net/">assimp</a> for 3D file formats loading.</li>
    <li><a href="https://developer.oculusvr.com/">libovr</a> for Oculus Rift control.</li>
</ul>

<h3>Support:</h3>
<ul>
   <li>The code is provided without any warranties whether expressed or implied.</li>
   <li>No support can be provided on installation, compiler or build issues. The
      framework was tested on several machines using MS Visual Studio 2013 as
      well as on Mac OSX using XCode with GCC or LLVM compiler.
   </li>
   <li>The code is provided under <a href="http://opensource.org/licenses/GPL-3.0">GNU General Puplic License (GPL)</a>. 
      This means in general, that you must provide your code as well under GPL if you 
      use this code.
   </li>
   <li>Feedback always welcome.</li>
</ul>

<p>
Authors: marcus.hudritsch@bfh.ch, marc.wacker@bfh.ch<br>
Date: September 2014<br>
Copyright (c): 2002-2014 Marcus Hudritsch, Kirchrain 18, 2572 Sutz, Switzerland
</p>