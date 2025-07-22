FOCUS tool (Feedback and Optimisation for CAD Utility Script)  


Version: 1.30  
Developed by Joe Palmer  
Purpose: to provide realtime feedback to CAD students using Autodesk Fusion 360 regarding key model metrics.  
Tool may be expanded in the future for batch marking of student work  
Initial release builds on previous code release AMR124_general_model_checker3.py which was used by some students in the 2019/2020 academic year.  
Visaul mockup of this tool was originally developed under the name new_table11.py  
ALL algorithm creation and implementation is the work of Joseph Palmer and is completely unique  
---------------------VERSION HISTORY---------------------------------------  
V0.1 visual mockup only, removed "command executed" prompt when pressing OK button  
V0.2 visual mockup only, added multiple information tabs, corrected command box title, added focus ascii logo  
V0.3 added function to interrogate and score a model relative to the conrod example, scores not yet displayed in the tool  
V0.4 key information displayed by the tool, scores and sliders still paceholder  
V0.5 sliders reporting scores correctly, some issues with algorithm, total score not yet working  
V0.6 Some Scoring algorithm issues corrected, placeholder values still present  
V0.7 changes to import conrod parameters from values.csv  
V0.8 dropdown list now reads model names from CSV file  
V0.9 major changes to class and definition structure to later allow inputchangedeventhandler to be implemented  
V0.91 structure changes ongoing  
V0.92 removed all references to version number in user facing utility. V1.0 targetted for marking algorithm working.  
V0.93 specific slider values displayed, utility updates with ideal values from excel (not user cad file info)  
V0.94 Trying to get inputchangedeventhandler to work.  
V1.00 Merged with working inputchanged event handler example  
V1.01 Tool is now reorting model properties correctly, an additional text box reports which drop down option the user has selected. Sliders and scores are stil placeholders.   
V1.02 In process of changing all sliders to global vars  
V1.03 Percentage score text updating with selection - dummy values only  
V1.04 Dead end don't use  
V1.05 All sliders and scores updating with dummy data  
V1.06 Scores only updating with correct data  
V1.07 All sliders and scores reporting properly and updating after each user change selection, total score not working  
V1.08 Total score reporting properly. Tool fully working except wordbank and code word.  
V1.09 wordbank and code word definitions written ans semi-working.  
V1.10 save issue  
V1.11 Wordbank feedback is updating properly, wordbank function itself needs review, not making sense.  
V1.12 Codeword functionality semi-working, textbox removed which mirrors user selection  
V1.15 First attempt at converting to add-in  
V1.20 Working as an Add-in, error on empty model and error when clicking hyperlinks remain.  
V1.30 Added exception handler for when the model is empty or contains no sketches (general divide by zero check). increased height of wordbank feedback box. Modified way in which resources are accessed to be Mac compatible.  
---------------------RELEASE HISTORY-----------------------------------------  
AMR124_general_model_checker3.py - Used for intial testing of automated feedback, implemented for 2019/2020 cohort.  
V1.20 Initial app store submission, rejected due to error on empty model.  
V1.30 F360 App Store Release!!!!!  
---------------------LONG TERM DEVELOPMENT----------------------  
change algorithm to count total model parameters rather than sketch dimensions  
create algorithm for 4-word code generator, this needs to be based on a unique identifer such as student user name, this would stop students sharing any codes. VLE quiz may not be capable of this. user username/userid to generate codeword  
centre wordbank and codeword text  
Refinement of scoring algorithm  
Adding hyperlinks to tab 3 causes popup error, investigate.  

Autodesk Fusion 360 App Store Link - https://apps.autodesk.com/FUSION/en/Detail/Index?id=2494541190963875504&appLang=en&os=Win64  

As of December 2021 this project is no longer in active development.  
