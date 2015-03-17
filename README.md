#Trick Apex Salesforce
Create table with apex:panelGrid in Salesforce to generate a PDF

##Sample code
###body
```
<apex:page renderAs="pdf" applyBodyTag="false">
     <apex:panelGrid columns="3" columnClasses="col1, col2, col3" styleClass="detail2" cellspacing="5" cellpadding="8">
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
    </apex:panelGrid>
</apex:page>
```
###style
```
<style> 
            .detail2{font: 10px; position:fixed; top:350px; left:25px; line-height:2em;}
            .col1 {width:315px; text-align:center;background-color: #00C979;text-align: left;}
            .col2 {width:5px; text-align:center; background-color: #D94838;}
            .col3 {width:75px; text-align:center; background-color: #34495E;}             
 </style>
```

#Output

![alt text](http://i.imgur.com/N8ognaP.png "Example")

