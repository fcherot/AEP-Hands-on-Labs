Lab  - Activation of Segments to a Destination (ExperienceEvent)
==========
<table style="border-collapse: collapse; border: none;" class="tab" cellspacing="0" cellpadding="0">

<tr style="border: none;">

<div align="left">
<td width="600" style="border: none;">
<table>
<tbody valign="top">
      <tr width="500">
            <td valign="top"><h3>Objective:</h3></td>
            <td valign="top"><br>In this exercise, we’ll share a segment created in a previous lab with the Salesforce Marketing Cloud destination configured in AEP.</br>
            </td>
     </tr>
     <tr width="500">
           <td valign="top"><h3>Prerequisites:</h3></td>
           <td valign="top"><br>DSS SFMC S3 Destination</td>
     </tr>
</tbody>
</table>
</td>
</div>

<div align="right">
<td style="border: none;" valign="top">

<table>
<tbody valign="top">
      <tr>
            <td valign="middle" height="70"><b>section</b></td>
            <td valign="middle" height="70"><img src="https://github.com/adobe/AEP-Hands-on-Labs/blob/master/assets/images/left_hand_nav_menu_segments.png?raw=true" alt="Segments"></td>
      </tr>
      <tr>
            <td valign="middle" height="70"><b>version</b></td>
            <td valign="middle" height="70">1.0.1</td>
      </tr>
      <tr>
            <td valign="middle" height="70"><b>date</b></td>
            <td valign="middle" height="70">2020-01-06</td>
      </tr>
</tbody>
</table>
</td>
</div>

</tr>
</table>

Instructions:
-----------------
1.	In the left navigation of AEP, select Destinations > Browse.
2.	Click ‘DSS SFMC S3 Destination’. 

![Demo](./images/destinations_travel_browse.png)

3.	Once you select the destination, click on ‘Edit Activation’. This takes you to the Activate flow.

![Demo](./images/destinations_travel_destination_edit.png)
 
4.	In Activate destination wizard, on the Select Segments page, select your version of the “Email Channel Online Reservation Abandoners” segment you created in the previous lab if it exists; otherwise, select any version of this segment.

![Demo](./images/destinations_travel_activate_flow_1.png)
 
5.	Select Next in the upper top corner of the workflow
6.	This step only applies for segments mapped to email marketing destinations.

![Demo](./images/destinations_travel_activate_flow_2.png)

7.	Click on ‘Add new field’ at the bottom
8.	Enter ‘homeAddress.stateProvince’
9.	Click on ‘Next’ in the upper top corner of the workflow
10.	On the Schedule page, you can see the start date for sending data to the destination, as well as the frequency of sending data to the destination.
11.	Click on ‘Next’ in the upper top corner of the workflow
12.	On the Review page, you can see a summary of your selection. Select Finish to confirm your selection and start sending data to the destination.

<br>
<br>
<br>

Return to [Lab Agenda Directory](https://github.com/adobe/AEP-Hands-on-Labs/blob/master/labs/retail/README.md#lab-agenda)
