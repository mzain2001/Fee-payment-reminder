# Fee-payment-reminder
A simple flow that reads excel data and sends out emails to students who have a fee payment pending.
Overview

This flow automates the process of sending out registration fee notifications. It eliminates the need for manual tracking by checking an Excel database and reaching out to recipients on a set schedule.

How it Works:

Schedule: The flow runs automatically at a pre-set interval (Recurrence).

Data Retrieval: It pulls a list of records from a specific Excel table.

Communication: For every row found in that table, the system automatically sends a customized email through Outlook to the relevant contact.

Key Benefits:

Ensures consistent communication without manual intervention.

Reduces the risk of missing fee notifications.
