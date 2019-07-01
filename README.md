# MigratingToolForFreshdesk

This Python project is used for migrating all the tech support agents and tickets information from old Aegis Helpdesk system to the online Freshdesk ticketing system. **This github project is used for source code maintainance and the raw data files (e.g., users.xml, tickets.csv etc. are not uploaded here).**

0. The users information are dumped into an .xml file. Run 0_generateContactFromXML.py to extract the customer details from the .xml file and migrate the customers details to Freshdesk system via Restful API.

1. Run 1_makeAgents.py to create the Agents in <companyName> from the Agents.txt file.

2. Run 2_filterSpam.py to filter the spam tickets and put the real tickets into <userfile.log>

3. Run 3_impticket.py to export the tickets in Ticket01.log into the <companyName> freshdesk server (Restful API is under development)
  
  <br>
  <br>
  <br>
  <br>
  <br>
  retriveOrder.py program is used for exporting the customer details from the Cubecart mysql database.
  
  
  









