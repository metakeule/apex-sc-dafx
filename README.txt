Damian Murphy, Mátyás Jani and Sten Ternström - November 2015.

Usual Disclaimer:
//
    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
//

A Guide to this directory:

README.rtf:
This file.

DAFx15.sc:
A SuperCollider Script for testing and running APEX-SC and KLVocalTract including how to generate the examples used in the DAFx Paper

data:
APEX data - the line to run APEX-SC in DAFx15.sc needs to point to this folder.

DAFx15_MurphyEtAl_FinalUpdated.pdf
The DAFx15 paper on which this work is based - updated from that available at http://www.ntnu.edu/web/dafx15/ to fix a few typos.

APEX_Client:
These are the additional APEX Client side SuperCollider Classes. They need to go somewhere SuperCollider can see them when compiling and running - typically on the Mac: /Library/Application Support/SuperCollider/Extensions

UGenClasses:
The Client Side SuperCollider Classes for the two server side UGens used in this implementation. Need to go in same directory as APEX_Cient files, e.g: /Library/Application Support/SuperCollider/Extensions

UGens:
These are the two compiled UGens - KLVocalTract and VocalTractArea. Versions here are Mac only, compiled, run and tested for OS10.7. Also need to go in same directory as APEX_Cient files, e.g: /Library/Application Support/SuperCollider/Extensions

UgenSourceCode:
Source code to build all three UGens. There is the required cmake file and the source code here, plus a helpful README file where I made some notes to get SuperCollider compiled from source and then these new UGens compiled. 

Acknowledgements:

The authors are indebted to Björn Lindblom and Christine Ericsdotter, both at Stockholm University, and to Johan Sundberg at KTH, for generously sharing their expertise and data, painstakingly acquired for the original APEX Windows 3.1 implementation, which was written by Johan Stark. The groundwork for the SuperCollider implementation of APEX was done in 2011 in the M.Sc. thesis of author Jani. The extended version presented here was developed in 2014- 2015 by authors Murphy and Ternström. We are grateful also to Gerhard Eckel and Ludvig Elblaus for advice and assistance with SuperCollider. The work was supported in part by the Swedish Research Council (VR), contract D-2013-0378.



