# HA-CSS-Color-Selector
The HA CSS Color Selector was created to allow a preview of color schemes for a card.  Icon, Brackground, Primary, and Secondary can be selected for preview.  The Hex value and CSS Color Name value is also displayed.  Select the item you want to preview the color and then select the color from the Color Grid.  You can select Icon, Background, Primary, Secondary from the Dropdown menu or you can optional create a Radio Button card.  Both are displayed below.  

![image](https://github.com/user-attachments/assets/b9a215fc-099e-40bd-b3bd-b7292bf73b46)   

**The following resources must be installed from HACS**  
	card-mod  
	mushroom   

 **Add the following Helpers**  
 input_text.selected_color  Get color selected from Color Grid   
 input_text.icon_c  Contains color value for Icon  
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
 
![image](https://github.com/user-attachments/assets/4a87a89c-fa5d-458a-98e1-43f3ec4e244a)  
 

**Create Color Grid Card**  
Paste grid_card_configuration.yml into new Manual Card to create  

![image](https://github.com/user-attachments/assets/7116af12-2eaf-42e6-82e4-bbc4d05a8ae5)  

**Create Preview Card**  
Paste preview_card.yml into new Manual Card to create  

![image](https://github.com/user-attachments/assets/268d5399-b4ef-4441-b548-ecdb23dc45ab)  

**Create Card Color Information Card**  
Paste card_color_information.yml into new Manual Card to create  

![image](https://github.com/user-attachments/assets/0fe3f832-024b-477d-9749-8c011051f4fa)  

**Create Card Item Options Card with Dropdown Menu**  There is a Dropdown card and Radio Button card.  You can create either one or both. 
Paste select_item_option.yml in new Manual Card to create  

![image](https://github.com/user-attachments/assets/8db98fdd-345a-497d-8ce2-29d62e9c4f99)  

**Create Card Options Card with Radio Buttons**  

![image](https://github.com/user-attachments/assets/4c5c176b-e537-4430-9326-dafb3f766198)







