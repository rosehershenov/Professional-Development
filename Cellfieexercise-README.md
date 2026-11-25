Install Cellfie as a plug-in on Protege. (see directions in dimension).    
Download https://docs.google.com/spreadsheets/d/12W8gtqKr3HatEn6c2qDGGCftREOUF8AU/edit?usp=sharing&ouid=106564155432496619943&rtpof=true&sd=true   

In “Tools”, choose “Create Axioms from Excel Workbook” (this will use Cellfie)

Choose the downloaded file above. 

Creating Transformation Rules

To start creating transformation rules, select the Add button at the transformation rule edit panel. An editor dialog will pop up where you can type the transformation expression.

Enter:

Start column: B

End column: B

Start row: 1

End row: +

In the rule box: 

    Class: @B*
    	    
        SubClassOf: @C*
            
This means that B is a subclass of C. Indentations and spaces are important. There are four spaces before “SubclassOf:”
    
Click “Generate Axioms”

Protege/Cellfie should generate 8 axioms. 
