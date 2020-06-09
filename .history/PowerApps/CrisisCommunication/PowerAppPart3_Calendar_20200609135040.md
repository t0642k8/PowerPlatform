# Welcome to Part 3 of the Crisis Communication Application 
### version 1

This section starts with the creation of the calendar page in order for people to set their status 
on the correct day(s).
<Table>
    <tr>
      <td> 1) A brand new screen has to be created. In the top of the screen select the new screen and from the 
              options select Calendar. When created it is created rename it to scrCalendar. </td>
    </tr>
    <tr> <td><a href="images4/PA4-1NewScreen.png"><img src="images4/PA4-1NewScreen.png" width="350"></a></td><td>&nbsp;</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 2) Click scrCalendar to select it and in the top menu ensure the left dropdown box says onVisible, Then enter the code 
              below. </td>
    </tr>
    <tr>
      <td><a href="images4/PA4-2.png"><img src="images4/PA4-2.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 3) In step 4 we will either delete Items we dont need or set the visible property to true. The OnVisible property is in the dropdown
              box and then the text box to the right erase everything and type true. </td>
    </tr>
    <tr>
      <td><a href="images4/PA4-3a.png"><img src="images4/PA4-3a.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
        <tr>
      <td> 4) Preform the actions in the graphic below.  </td>
    </tr>
    <tr>
      <td><a href="images4/PA4-3.png"><img src="images4/PA4-3.png" width="550"></a></td>
    </tr>
    <tr>
      <td>Note: when you delete dropDownCalendarSection1 there will be errors that show up.
               This is expected and other controls rely on this control. We will fix them.</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 5) On the left panel click to    ighted </td>
    </tr>
    <tr>
      <td><a href="images4/PA4_Person.png"><img src="images4/PA4_Person.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 6  Ensure that the first drop down box say "OnSelect" and in the function box enter "Navigate(scrPII)" </td>
    </tr>
    <tr>
      <td><a href="images4/PA5Function.png"><img src="images4/PA5Function.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
   <tr>
      <td> 6) On the left panel, click to select the screen scrPII </td>
    </tr>
    <tr>
      <td><a href="images4/PA_P2_6clicktoSelect.png"><img src="images4/PA_P2_6clicktoSelect.png" width="250"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 7) On this screen is a diagnoser is correct. We are going to make
             some labels for information bu. </td>
    </tr>
    <tr>
      <td><a href="images4/PA2_7_InsertALabel.png"><img src="images4/PA2_7_InsertALabel.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 8)  Rename Label1 (or the new label) to lblCenter</td>
    </tr>
    <tr>
      <td><a href="images4/PA2_8_Reame.png"><img src="images4/PA2_8_Reame.png" width="250"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>   
    <tr>
      <td> 9) Single click on lblCenter to select it, then nel. </td>
    </tr>
    <tr>
      <td> <table>
             <tr>
               <td>Text =  Center:</td>
               <td>Font Size =  24</td>
               <td>Position =  60  x 200 </td>                              
              </tr>
            </table>    
             </td>
    </tr>
    <tr>
      <td><a href="images4/PA2-9.png"><img src="images4/PA2-9.png" width="250"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 10) Below the position parameters in the right panel change the following </td>
    </tr>
        <tr>
      <td> <table>
             <tr>
               <td>Size =  200 x 50</td>
               <td>Background Color =  Yellow </td>                              
              </tr>
            </table>    
             </td>
    </tr>
    <tr>
      <td><a href="images4/pa2-10.png"><img src="images4/pa2-10.png" width="250"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 11) On the left, right click lblCenter and select copy</td>
    </tr>
    <tr>
      <td><a href="images4/PA2_RightClickCenter.png"><img src="images4/PA2_RightClickCenter.png" width="250"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr> 
    <tr>
      <td> 12) Right Click scrPII to select it. Select paste.</td>
    </tr>
    <tr>
      <td><a href="images4/pa11.png"><img src="images4/pa11.png" width="250"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr> 
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 13) Rename the new label to lblDirectorate</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 14) Single click on lblDirectorate to select it, then in the right panel make the following changes. </td>
    </tr>
    <tr>
      <td> <table>
             <tr>
               <td>Text =  Directorate:</td>
               <td>Font Size =  24</td>
               <td>Position =  60  x 255 </td>                              
              </tr>
            </table>    
             </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 15) Right click on lblDirectorate and copy it to make another label. Name it lblDivisionBranch.
        Then in the left panel make the following changes </td>
    </tr>
    <tr>
      <td> <table>
             <tr>
               <td>Text =  Division / Branch:</td>
               <td>Font Size =  24</td>
               <td>Position =  60  x 315 </td>   
               <td>Size =  268  x 50 </td>                              
              </tr>
            </table>    
             </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 16) Right click on lblDirectorate and copy it to make another label. Name it lblJobTitle.
        Then in the left panel make the following changes </td>
    </tr>
    <tr>
      <td> <table>
             <tr>
               <td>Text =  Job Title:</td>
               <td>Font Size =  24</td>
               <td>Position =  60  x 382 </td>   
               <td>Size =  160  x 50 </td>                              
              </tr>
            </table>    
             </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 17) Your screen should look like the following</td>
    </tr>
    <tr>
      <td><a href="images4/pa_lookLike.png"><img src="images4/pa_lookLike.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr> 
  <tr>
      <td> 18) Right click on lblCenter on the left panel. Then select copy. Click on scrPII to select it
               then right click and select paste. Name this new label lblTcenter . In the right panel make the follow changes.
                </td>
 </tr>
 <tr>
      <td> <table>
             <tr>
               <td>Text =  </td>
               <td>Position =  284  x 200 </td>   
               <td>Size =  200  x 50 </td> 
               <td>Background Color =  light grey </td>                                               
             </tr>
            </table>    
             </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 19) On the left panel, click tp select App , then ensure the left drop down box is set to OnStart.
       </td>
    </tr>
    <tr>
      <td><a href="images4/PA2_19a.png"><img src="images4/PA2_19a.png" width="550"></a></td>
    </tr>
        <tr>
      <td> 20) With the lblTcenter label highlighted, on the top menu select text in the first dropdown and type this formula
             in the text box to the right.   Office365Users.MyProfile().City </td>
    </tr>
    <tr>
      <td><a href="images4/PA2-19.png"><img src="images4/PA2-19.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
   <tr>
      <td> 20) On the left panel, Right click on lblTcenter and select copy </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
        <tr>
      <td>&nbsp;</td>
    </tr>  
       <tr>
      <td> 21) On the left panel, Click on scrPII to select it, Then right click and select Paste. Rename this
               label lblTdir </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
        <tr>
      <td>&nbsp;</td>
    </tr>  
        <tr>
      <td> 22) With lblTdir highted, on the top menu select "text" in the first dropdown and type this formula
             in the text box to the right type  Dir </td>
    </tr>
    <tr>
      <td><a href="images4/PA2_22.png"><img src="images4/PA2_22.png" width="550"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    </Table>