# Send certain Emails to Teams
 
Below you will find the instructions that will allow you to automatically
save an email directly into a team's channel. Email can be automatically saved
to most Office 365 applications. These are instructions how to save An email to 
a teams channel by the use of Power Automate.

This project will scan for the word Telework in the subject line of the message and move it 
teams. Power Automate will automatically scan a documents subject line for the word "Telework"
then it will transfer the document into the teams application.


<table>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 1) Login to Office 365  (www.office.com) </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 2) Select Power Automate </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pa2.png"><img src="images2/pa2.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>  
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 3) Click on the create tab. </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pa3.png"><img src="images2/pa3.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>     
<tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 4) Select Automated Flow </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pa4png.png"><img src="images2/pa4png.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>  
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 5) Create your new flow name, then type the word "email" into the search box. From the selections that
              the search returns select the one that says "When Email arrives". </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pa5.png"><img src="images2/pa5.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>  
  <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 6)  Inside the next screen, you will find the Power Automate workbench. The first box on each screen is called the "Trigger".
               The trigger that was orginally chosen from the previous screen is shown below. Click on the down arrow to access the advanced setting.
      </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp6.png"><img src="images2/pp6.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>  
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 7) Once you have accessed the advanced setting as advised in the previous screen, it is time to set up your email settings
              to capture all emails that has the word "Telework" in the subject line. On the last line in the screen you will find a text box named
              Subject filter. In this box Type "Telework"</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp7.png"><img src="images2/pp7.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr> 
   <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 8) See the sample below.  </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp8.png"><img src="images2/pp8.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>   
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 9) Click on next step as seen below.</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp9.png"><img src="images2/pp9.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>   
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 10) In the search box type "Teams". then press enter.  </td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp10.png"><img src="images2/pp10.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>   
     <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 11) Next you will locate will locate the "Post a message (V3)(preview) Microsoft Teams" icon. .</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp11.png"><img src="images2/pp11.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>  
         <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 12) In the Teams Drop Down Select your Teams Site. When that is select select the chanel in the other dropdown box</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp12.png"><img src="images2/pp12.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>   
             <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 13) Next, you will click on the box labeled "Message" then the dynamic content menu will appear.
                You will click on "body"</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp13.png"><img src="images2/pp13.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr> 
             <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 14) Next Click on save. When the saving is complete the test icon (which was greyed out) should be active.
                 Click on test</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp14.png"><img src="images2/pp14.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>    
              <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td> 15) Select I'll Preform the Trigger action , then select save and test</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td><a href="images2/pp15.png"><img src="images2/pp15.png" width="700"></a></td>
    </tr>
    <tr>
      <td>&nbsp;</td>
    </tr>                                          
</table>