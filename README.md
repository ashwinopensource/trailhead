<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=Generator content="Microsoft Word 15 (filtered)">
<title>Show Visualforce page in Salesforce1 Mobile</title>
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
@font-face
	{font-family:"Segoe UI Semilight";
	panose-1:2 11 4 2 4 2 4 2 2 3;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:0in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
h1
	{mso-style-link:"Heading 1 Char";
	margin-top:12.0pt;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:0in;
	margin-bottom:.0001pt;
	line-height:107%;
	page-break-after:avoid;
	font-size:16.0pt;
	font-family:"Calibri Light","sans-serif";
	color:#2E74B5;
	font-weight:normal;}
h2
	{mso-style-link:"Heading 2 Char";
	margin-top:2.0pt;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:0in;
	margin-bottom:.0001pt;
	line-height:107%;
	page-break-after:avoid;
	font-size:13.0pt;
	font-family:"Calibri Light","sans-serif";
	color:#2E74B5;
	font-weight:normal;}
p.MsoHeader, li.MsoHeader, div.MsoHeader
	{mso-style-link:"Header Char";
	margin:0in;
	margin-bottom:.0001pt;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
p.MsoFooter, li.MsoFooter, div.MsoFooter
	{mso-style-link:"Footer Char";
	margin:0in;
	margin-bottom:.0001pt;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
a:link, span.MsoHyperlink
	{color:#0563C1;
	text-decoration:underline;}
a:visited, span.MsoHyperlinkFollowed
	{color:#954F72;
	text-decoration:underline;}
p
	{margin-right:0in;
	margin-left:0in;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:.5in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:.5in;
	margin-bottom:.0001pt;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:0in;
	margin-left:.5in;
	margin-bottom:.0001pt;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:.5in;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
span.Heading1Char
	{mso-style-name:"Heading 1 Char";
	mso-style-link:"Heading 1";
	font-family:"Calibri Light","sans-serif";
	color:#2E74B5;}
span.Heading2Char
	{mso-style-name:"Heading 2 Char";
	mso-style-link:"Heading 2";
	font-family:"Calibri Light","sans-serif";
	color:#2E74B5;}
span.HeaderChar
	{mso-style-name:"Header Char";
	mso-style-link:Header;}
span.FooterChar
	{mso-style-name:"Footer Char";
	mso-style-link:Footer;}
.MsoPapDefault
	{margin-bottom:8.0pt;
	line-height:107%;}
 /* Page Definitions */
 @page WordSection1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0in;}
ul
	{margin-bottom:0in;}
-->
</style>

</head>

<body lang=EN-US link="#0563C1" vlink="#954F72">

<div class=WordSection1>

<h1>Learning Objective</h1>

<p style='margin:0in;margin-bottom:.0001pt'><span style='font-size:11.0pt;
font-family:"Calibri","sans-serif";color:black'>&nbsp;</span></p>

<p style='margin:0in;margin-bottom:.0001pt'><span style='font-size:10.0pt;
font-family:"Segoe UI Semilight","sans-serif";color:black'>After completing
this Quick Start tutorial you will be able to:</span></p>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:.25in;
margin-bottom:.0001pt;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol;color:black'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif";
color:black'>Create Visualforce page for Salesforce1 mobile</span></p>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:.25in;
margin-bottom:.0001pt;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol;color:black'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif";
color:black'>Creating publisher action, mobile tab and mobile card</span></p>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:.25in;
margin-bottom:.0001pt;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol;color:black'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif";
color:black'>Use visualforce page to various places in Salesforce1</span></p>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:.25in;
margin-bottom:.0001pt'><span style='font-size:11.0pt;font-family:"Calibri","sans-serif";
color:black'>&nbsp;</span></p>

<h1>Ready a Visualforce Page<span style='font-size:11.0pt;line-height:107%;
font-family:"Calibri","sans-serif";color:black'>&nbsp;</span></h1>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:27.0pt;
margin-bottom:.0001pt'><span style='font-size:11.0pt;font-family:"Calibri","sans-serif";
color:black'>&nbsp;</span></p>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:.25in;
margin-bottom:.0001pt;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:"Segoe UI Semilight","sans-serif";color:black'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif";
color:black'>Create Visualforce page for Salesforce1 mobile</span></p>

<p style='margin-top:0in;margin-right:0in;margin-bottom:0in;margin-left:.25in;
margin-bottom:.0001pt;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:"Segoe UI Semilight","sans-serif";color:black'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif";
color:black'>From Setup, <b>Develop</b> | <b>Pages</b>, and then clicking <b>New</b>.</span></p>

<p class=MsoListParagraph style='margin-left:.25in;text-indent:-.25in;
line-height:normal'><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'>Copy
following code in Visualforce editor window</span></p>

<p class=MsoNormal style='margin-left:.25in;line-height:normal'><span
style='color:#C55A11'>&lt;apex:page title=&quot;Trailhead QuickStart&quot;
standardController=&quot;Account&quot; showHeader=&quot;false&quot;&gt;</span></p>

<p class=MsoNormal style='margin-left:.25in;line-height:normal'><span
style='color:#C55A11'>&lt;h1&gt; Hello World, Hello Dreamforce! &lt;/h1&gt;</span></p>

<p class=MsoNormal style='margin-left:.25in;line-height:normal'><span
style='color:#C55A11'>&lt;/apex:page&gt;</span></p>

<p class=MsoListParagraph style='margin-left:.25in;text-indent:-.25in;
line-height:normal'><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'>4.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'>Check</span></b><span
style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'> the <b>Available
for Salesforce mobile apps</b> checkbox</span></p>

<p class=MsoNormal style='margin-left:.25in'>&nbsp;</p>

<p class=MsoNormal><img width=689 height=424 id="Picture 17"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image001.png"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoListParagraph style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Save</b> button</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:107%;font-family:
"Segoe UI Semilight","sans-serif"'>Great! You just created your first
Visualforce page.</span></p>

<p class=MsoNormal>&nbsp;</p>

<h1>Create a Salesforce1 Mobile Tab</h1>

<p class=MsoListParagraphCxSpFirst style='margin-left:22.5pt;text-indent:-22.5pt'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>From
<b>Setup</b>, click <b>Create</b> | <b>Tabs</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:22.5pt;text-indent:-22.5pt'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>New</b> on <b>Visuaforce Tabs</b> section</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:22.5pt;text-indent:-22.5pt'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Select
<b>HelloDreamforce</b> page from <b>Visualforce Page</b> dropdown</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:22.5pt;text-indent:-22.5pt'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>4.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Name
the tab “Trailhead Demo” in <b>Tab Label</b></span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:22.5pt;text-indent:-22.5pt'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Select
any Tab Style from <b>Tab Style</b> lookup</span></p>

<p class=MsoNormal><img width=689 height=457 id="Picture 2"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image002.png"></p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>6.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Next</b> until you don’t reach to <b>Step 3: Add to Custom Apps</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>7.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Deselect
<b>Include Tab</b> checkbox</span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>8.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Save</b></span></p>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:107%;font-family:
"Segoe UI Semilight","sans-serif"'>Great! You have just created Salesforce1
Mobile Tab. </span></p>

<p class=MsoNormal>&nbsp;</p>

<h2>Now let’s add the mobile tab to Salesforce1 Mobile</h2>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>From
<b>Setup</b>, click <b>Create</b> | <b>Tabs</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Edit</b> before to the tab “Trailhead Demo” on <b>Visuaforce Tabs</b>
section</span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Check
the <b>Salesforce Classic Ready</b> checkbox</span></p>

<p class=MsoNormal><img width=444 height=300 id="Picture 3"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image003.png"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>4.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Save</b></span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>From
Setup, click <b>Selesforce1 Setup</b> | <b>Navigation Menu</b> link</span></p>

<p class=MsoNormal><img width=689 height=315 id="Picture 5"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image004.png"></p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>6.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Select
Trailhead Demo and click Add to move into <b>Selected</b> list</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>7.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Use
<b>Up</b> and <b>Down</b> to put it as first item in list</span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>8.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Save</b></span></p>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:107%;font-family:
"Segoe UI Semilight","sans-serif"'>Awesome! You have just enabled the
visualforce page for Salesforce1 mobile App. Login to the app, you would see
your page as:</span></p>

<p class=MsoNormal><img width=689 height=469 id="Picture 6"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image005.png"></p>

<p class=MsoNormal>&nbsp;</p>

<h1>Create the Visualforce page as an Action in Salesforce1 App</h1>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>From
Setup, click on <b>Customize | Accounts | Buttons, Links and Actions</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>New Action</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Select
<b>Action Type</b> “Custom Visualforce” from dropdown</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>4.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Select
<b>Visualforce Page</b> “HelloDreamforce” from dropdown</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Set
<b>Label</b> “Say Hello Trailhead”</span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'>6.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Save</b></span></p>

<p class=MsoNormal><b><img width=537 height=401 id="Picture 7"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image006.png"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:107%;font-family:
"Segoe UI Semilight","sans-serif"'>You have just defined a new action which can
be used on Account object. Let’s use it in Salesforce1</span></p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>From
Setup, click <b>Customize | Accounts | Page Layouts</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Edit</b> before to <b>Account Layout</b></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>In
page layout editor Select <b>Quick Action</b> in navigation panel</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-align:justify;
text-indent:-.25in'>4.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Drag
<b>Say Hello Trailhead </b>action and drop it to <b>Quick Action in Publisher</b>
section</span></p>

<p class=MsoListParagraphCxSpMiddle>&nbsp;</p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:.25in;text-align:justify'><span
style='position:absolute;z-index:251662336;left:0px;margin-left:309px;
margin-top:463px;width:373px;height:265px'><img width=373 height=265
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image007.png"></span> <img
width=655 height=354 id="Picture 8"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image008.png"> </p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Quick Save</b> </span></p>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:107%;font-family:
"Segoe UI Semilight","sans-serif"'>You have just enabled the Visualforce as a
Quick Action to your Account. Let’s check it Salesforce1 by opening any Account
record</span></p>

<p class=MsoNormal><img width=257 height=471 id="Picture 18"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image009.png"></p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>6.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Same
way, in page layout editor Select <b>Visualforce Pages</b> in navigation panel</span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>7.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Drag
<b>Say Hello Trailhead </b>Visualforce page and drop it to <b>Mobile Cards
(Salesforce1 Only)</b> section</span></p>

<p class=MsoNormal><img width=721 height=464 id="Picture 14"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image010.jpg"></p>

<p class=MsoListParagraph style='margin-left:.25in;text-indent:-.25in'><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>8.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><span
style='font-size:10.0pt;line-height:107%;font-family:"Segoe UI Semilight","sans-serif"'>Click
<b>Save</b></span></p>

<p class=MsoNormal><b><span style='font-size:10.0pt;line-height:107%;
font-family:"Segoe UI Semilight","sans-serif"'>&nbsp;</span></b></p>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:107%;font-family:
"Segoe UI Semilight","sans-serif"'>You have just set Visualforce page as mobile
card in Salesforce1 page. Let’s check it by opening any Account record’s <b>Related</b>
tab in Salesforce1 App</span></p>

<p class=MsoNormal><img width=258 height=466 id="Picture 15"
src="Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image011.png"></p>

<p class=MsoNormal>&nbsp;</p>

<h1>Summary</h1>

<p class=MsoNormal>With Tutorial you have learned the ways a Visualforce can be
used in Salesforce mobile1 app. Each way has its own benefits. Now whenever you
need to add a Visualforce you know the ways and how to do it.</p>

<h1>Resources</h1>

<p class=MsoNormal style='margin-top:0in;margin-right:0in;margin-bottom:0in;
margin-left:.25in;margin-bottom:.0001pt;text-indent:-.25in;line-height:normal'><span
style='font-size:10.0pt;font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'><a
href="https://help.salesforce.com/HTViewHelpDoc?id=actions_overview_global.htm"
target="_blank" title="HTML (New Window)"><span style='text-decoration:none'>Global
Actions</span></a></span></p>

<p class=MsoNormal style='margin-top:0in;margin-right:0in;margin-bottom:0in;
margin-left:.25in;margin-bottom:.0001pt;text-indent:-.25in;line-height:normal'><span
style='font-size:10.0pt;font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'><a
href="https://help.salesforce.com/HTViewHelpDoc?id=predefined_field_values_notes.htm"
target="_blank" title="HTML (New Window)"><span style='text-decoration:none'>Notes
on Predefined Field Values for Quick Actions</span></a></span></p>

<p class=MsoNormal style='margin-top:0in;margin-right:0in;margin-bottom:0in;
margin-left:.25in;margin-bottom:.0001pt;text-indent:-.25in;line-height:normal'><span
style='font-size:10.0pt;font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'><a
href="https://help.salesforce.com/HTViewHelpDoc?id=assigning_global_publisher_layouts_to_profiles.htm"
target="_blank"><span style='text-decoration:none'>Assign Global Publisher
Layouts to User Profiles</span></a></span></p>

<p class=MsoNormal style='margin-top:0in;margin-right:0in;margin-bottom:0in;
margin-left:.25in;margin-bottom:.0001pt;text-indent:-.25in;line-height:normal'><span
style='font-size:10.0pt;font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'><a
href="https://intmist.wordpress.com/2014/02/16/salesforce1-look-and-feel-customise-visualforce-pages-for-salesforce1/"><span
style='text-decoration:none'>Salesforce1 Look and Feel in Visualforce pages</span></a></span></p>

<p class=MsoNormal style='margin-top:0in;margin-right:0in;margin-bottom:0in;
margin-left:.25in;margin-bottom:.0001pt;text-indent:-.25in;line-height:normal'><span
style='font-size:10.0pt;font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-size:10.0pt;font-family:"Segoe UI Semilight","sans-serif"'><a
href="https://intmist.wordpress.com/2014/03/23/show-custom-visualforce-page-in-salesforce1-setup-publisher-action-and-check-in-using-salesforce1-app/"><span
style='text-decoration:none'>Show Custom Visualforce page in Salesforce1. Setup
publisher action to allow user to check-in using Salesforce1&nbsp;app</span></a></span></p>

<p class=MsoNormal>&nbsp;</p>

</div>

</body>

</html>
