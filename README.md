# MigratingToolForFreshdesk

This Python project is used for migrating all the tech support agents and tickets information from old Aegis Helpdesk system to the online Freshdesk ticketing system.

The users information are dumped into an .xml file.

Run 0_generateContactFromXML.py to extract the customer details from the .xml file and migrate the customers details in Freshdesk system via Restful API.

