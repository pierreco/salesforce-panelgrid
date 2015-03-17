#Trick Apex Salesforce
Create table with apex:panelGrid in Salesforce to generate a PDF

##Sample code
###body
```
<apex:page renderAs="pdf" applyBodyTag="false">
     <apex:panelGrid columns="3" columnClasses="col1, col2, col3, col4, col5, col6" styleClass="detail">
        <apex:outputText >Sample1</apex:outputText>
        <apex:outputText >Sample1</apex:outputText>
        <apex:outputText >Sample1</apex:outputText>
        <apex:outputText >Sample1</apex:outputText>
        <apex:outputText >Sample1</apex:outputText>
        <apex:outputText >Sample1</apex:outputText>
        <apex:outputText >Sample2</apex:outputText>
        <apex:outputText >Sample2</apex:outputText>
        <apex:outputText >Sample2</apex:outputText>
        <apex:outputText >Sample2</apex:outputText>
        <apex:outputText >Sample2</apex:outputText>
        <apex:outputText >Sample2</apex:outputText>
        <apex:outputText >Sample3</apex:outputText>
        <apex:outputText >Sample3</apex:outputText>
        <apex:outputText >Sample3</apex:outputText>
        <apex:outputText >Sample3</apex:outputText>
        <apex:outputText >Sample3</apex:outputText>
        <apex:outputText >Sample3</apex:outputText>
        <apex:outputText >Sample4</apex:outputText>
        <apex:outputText >Sample4</apex:outputText>
        <apex:outputText >Sample4</apex:outputText>
        <apex:outputText >Sample4</apex:outputText>
        <apex:outputText >Sample4</apex:outputText>
        <apex:outputText >Sample4</apex:outputText>
        <apex:outputText >Sample5</apex:outputText>
        <apex:outputText >Sample5</apex:outputText>
        <apex:outputText >Sample5</apex:outputText>
        <apex:outputText >Sample5</apex:outputText>
        <apex:outputText >Sample5</apex:outputText>
        <apex:outputText >Sample5</apex:outputText>
        <apex:outputText >Sample6</apex:outputText>
        <apex:outputText >Sample6</apex:outputText>
        <apex:outputText >Sample6</apex:outputText>
        <apex:outputText >Sample6</apex:outputText>
        <apex:outputText >Sample6</apex:outputText>
        <apex:outputText >Sample6</apex:outputText>
    </apex:panelGrid>
</apex:page>
```
###style
```
<style> 
           .detail td {padding: 5px, 13px}
            .col1 {width:315px; text-align: left;}
            .col2 {width:5px; text-align:center; }
            .col3 {width:75px; text-align: right;}
            .col4 {width:45px; text-align:center; }     
            .col5 {width:25px; text-align:center; }     
            .col6 {width:90px;  text-align: right;}               
 </style>
```

#Output

![alt text](http://i.imgur.com/N8ognaP.png "Example")

