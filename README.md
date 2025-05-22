# HA-CSS-Color-Selector
The HA CSS Color Selector was created to allow a preview of color schemes for a card.  Icon, IconBackground, Brackground, Primary, and Secondary can be selected for preview.  The Hex value and CSS Color Name value is also displayed.  Select the item you want to preview the color and then select the color from the Color Grid.  You can select Icon, Background, Primary, Secondary from the Dropdown menu or you can optional create a Radio Button card.  Both are displayed below.  

![image](https://github.com/user-attachments/assets/4f42542c-bd66-4144-bce5-c8e16f0072b6)
   

**The following resources must be installed from HACS**  
	card-mod  
	mushroom   

 **Add the following Helpers**  
 input_text.selected_color  Get color selected from Color Grid   
 input_text.icon_c  Contains color value for Icon  
 input_text.icon_background_c color value for Icon Background  
 input_text.background_c Contains color value for Background   
 input_text.primary_c  Contains color value for Primary text   
 input_text.secondary_c  Contains color value for Secondary text   
 input_select.card_configuration  Contains options to select to preview color (Icon, Background, Primary, Secondary)  

**Create Automation or NodeRed Flow** 
 Some prefer Automations or NodeRed I have provide code for both.  **Install only one.**  
 **Create Automation**  
 Paste Card_Color_Configuration_Automation.yml into a new Automation  
 **Create NodeRed Flow**  (don't create if you created the automation)  
 Import flows.json into NodeRed  
 ![image](https://github.com/user-attachments/assets/518fb66f-75fc-4d02-a699-37692d8c5300)  

 

**Create Color Grid Card**  
Paste grid_card_configuration.yml into new Manual Card to create  

![image](https://github.com/user-attachments/assets/7116af12-2eaf-42e6-82e4-bbc4d05a8ae5)  

**Create Preview Card**  
Paste preview_card.yml into new Manual Card to create  

![image](https://github.com/user-attachments/assets/eb5c945b-65be-4198-81d0-61225bd86823)    

**Create Card Color Information Card**  
Paste card_color_information.yml into new Manual Card to create  

![image](https://github.com/user-attachments/assets/60b8c024-f131-4737-9152-c2e3c6f62943)  

  
 

**Create Card Item Options Card with Dropdown Menu**  There is a Dropdown card and Radio Button card.  You can create either one or both. 
Paste select_item_option.yml in new Manual Card to create  

![image](https://github.com/user-attachments/assets/2db1a0e8-42d1-4fe4-835c-4229221ca91d)  
  

**Create Card Options Card with Radio Buttons**  
Paste select_item_option_radiobutton.yml in new Manual Card to create  
![image](https://github.com/user-attachments/assets/925d28d2-20bc-48f8-b878-9c4579392e83)






