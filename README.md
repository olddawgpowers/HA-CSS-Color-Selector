# HA-CSS-Color-Selector
The HA CSS Color Selector was created to allow a preview of color schemes for a card.  Icon, IconBackground, Brackground, Primary, and Secondary can be selected for preview.  The Hex value and CSS Color Name value is also displayed.  Select the item you want to preview the color and then select the color from the Color Grid.  You can select Icon, Background, Primary, Secondary from the Dropdown menu or you can optional create a Radio Button card.  Both are displayed below.  

![image](https://github.com/user-attachments/assets/4f42542c-bd66-4144-bce5-c8e16f0072b6)
   

**The following resources must be installed from HACS**  
If you do not have HACS installed or are not familiar with HACS there are some good guides available.  Both card-mod and mushroom have instructions for installation. They both can be installed using HACS.  
	- card-mod  
	- mushroom   
 
 ![image](https://github.com/user-attachments/assets/f4bafde9-761a-4f48-a42b-02d557585562)  

![image](https://github.com/user-attachments/assets/7bf0d6af-a3d3-4483-8e65-f9d23a15aefd)  

If installed, they will show in your resources  

![image](https://github.com/user-attachments/assets/01df9178-609a-4442-b37e-c1b4e0f73d7d)



 **Add the following Helpers**  
 **They are case and text-sensitive, enter exactly as shown**  
- input_text.selected_color  	(Get color selected from Color Grid)       
- input_text.icon_c  		(Contains color value for Icon)  
- input_text.icon_background_c 	(Contains color value for Icon Background)  
- input_text.background_c 	(Contains color value for Background0   
- input_text.primary_c  		(Contains color value for Primary text)   
- input_text.secondary_c  	(Contains color value for Secondary text)
- input_select.card_configuration  (Contains options to select to preview color Icon, Background, Primary, Secondary)  

**Use the Text Helper for input_text**    
![image](https://github.com/user-attachments/assets/448afb29-3814-4172-9a6b-8b3014e3ac27)  


 
  
 **Use the Dropdown Helper for input_select**      
![image](https://github.com/user-attachments/assets/2e6a9027-f903-4786-8512-e348aaf59f43)  
      


**Create Automation or NodeRed Flow** 
 Some prefer Automations or NodeRed I have provide code for both.  **Install only one.**  
 **Create Automation**  
 Paste Card_Color_Configuration_Automation.yml into a new Automation  
 **Create NodeRed Flow**  (don't create if you created the automation)  
 Import flows.json into NodeRed  
 ![image](https://github.com/user-attachments/assets/518fb66f-75fc-4d02-a699-37692d8c5300)  

 
**CREATING CARDS**  
All cards are created using the Manual Card

![image](https://github.com/user-attachments/assets/cc3f9270-3261-4edf-aa0c-0c58f4a9d15b)  

**Tip**
Be sure to delete or paste over the **type:""** pasting the code in.  

![image](https://github.com/user-attachments/assets/0c15787e-055f-447a-83cb-03782092e7ae)   

It should look like this before pasting in the code.

![image](https://github.com/user-attachments/assets/0ee7e5bd-fbb5-48de-8a5e-5b3e0f5cd00b)

If you have pasted the code correctly, you should see a preview of the card.  

![image](https://github.com/user-attachments/assets/0f496c37-6731-4546-b835-ae109aa45b37)


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






