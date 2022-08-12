# VbaLinkBudBackup

This file is for design and management of link budget of Indoor distributed control system (DCS)  network. The aim for this project is to automate the tedious calculations in designing routing of feeder cable and choice of coupler in the whole rf network.

 ## Content

1. [Introduction](#md-header2-introduction)
2. [User Manual](#md-header2-user-manual)
    1. [Set up visio file](#md-header3-set-up)
    2. [(Optional) Set up fast key for macro](#md-header3-fast-key)
    3. [How To Use](#md-header3-how-to-use)

<h2 id="md-header2-introduction">Introduction </h2>
The main problem in indoor DCS system is the complexity in calculation to reach a balance of power output in every antenna. Similar to every distrubuted system (e.g. Electiricty, Water distrubuted system), the system has a source to distrubute to every descending separation point (couplers) and eventually reach the 
output (antenna). The complexity of DCS system design comes from the limitation in construction site, mainly the pathway restricted and the antenna location pre-requested in tender by clients. To ensure the calculations reach the demanded power output (RSRP), link budget calculation is required. Without automation, 
we need to care about the choice of couplers, length and routing of feeder cables. Changing a coupler will alter the descendents' output which consisted in the same routing, which makes link budgets design difficult and complex.<br><br>
  
This project focus on calculation of RSRP output from antenna by subtracting the coupling loss and feeder loss in the whole pathway from source to ouput antenna. Visio is ultilized as GUI for showcase of link budget and DCS network design. 

<h2 id="md-header2-user-manual"> User Manual </h2>

<h3 id="md-header3-set-up"> Set up visio file </h3>
If you already have a visio file with this code, just delete all contents in the document. The document is ready for use. <br><br>

1. For setting up visio document, you need to open Visio first. Press Development tab in toolbar and you can see Visual Basic Editor (VBE). Press it to enter VBE.
<br>___image required___
2. Download all files from this project, drag all VBA files (___.bas, .frm, .cls file only___) to VB Editor as follow:
<br>___image required___
3. Close VB Editor. Back to Visio file.
4. Choose ___File >>> Shapes >>> Open Stensils...,___ a file dialog will pop up. Choose ___.vss file___ in this project.
<br>___image required___
5. You can see the stensil with shapes shown up. It is recommended to put all shapes to document stensil. The document is set up.<br>
<br>___check if need to make dynamic connector___

<h3 id="md-header3-fast-key"> (Optional) Set up fast key for macro</h3>
1. Press run macro, from __Macro in:__ dropdown list, select **A_main** 
2. Select __ShowLinkBudget__ from list, Press __Option...__ to assign shortcut key. Press ___Shift + D___ and press __Ok__.<br>
3. Select __ExportLinkBudget__ from list, Press __Option...__ to assign shortcut key. Press ___Shift + F___ and press __Ok__.<br>
4. Back to __Macro in:__ dropdown list, select __DC_AutoNumbering__<br>
5. Select __ActivateForm__ from list, Press __Option...__ to assign shortcut key. Press __Shift + W__ and press __Ok__. <br>

<h3 id="md-header3-how-to-use"> How To Use</h3>
2. Press and drag ___Start Block___ to your page.
<br>___image required___
3. Press and drag ___Start Block___ to your page

