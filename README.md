# BT_CNPMTT
Q1:
Functional requirements:
  The payment can be made by some online payment service such as Momo wallet, Samsung Pay, Apple Pay, etc.
  order food before coming
  Notification 
  Estimate preparing time
  allow members to re-charge and use their payment account

Non-functional requirements:
  no important information is leaked to non-authorized persons.

Q3: Identify Hardware failures, Software failures, and Operational failures for the system 
  1. Hardware Failures
  Server Failures: Physical servers may crash or malfunction, causing downtime for the application.
  Network Issues: Routers or switches can fail, leading to connectivity problems between users and the system.
  Database Storage Failures: Hard disk failures or RAID failures can result in data loss or inaccessibility.
  Point of Sale (POS) Device Failures: Malfunctioning POS systems in restaurants can prevent order taking and payment processing.
  Printer Failures: Issues with receipt or kitchen printers may disrupt order processing and fulfillment.
  2. Software Failures
  Application Bugs: Errors in the code can cause crashes or incorrect order processing.
  Database Corruption: Problems with data integrity can lead to lost or corrupt order information.
  Integration Failures: Issues with APIs or services that connect to third-party providers (like payment processors) can prevent transactions from completing.
  User Interface Errors: Design flaws can lead to a confusing experience, resulting in incorrect orders or user frustration.
  Dependency Failures: Failure of third-party libraries or services that the food order system relies on may cause disruptions.
  3. Operational Failures
  Human Errors: Mistakes made by staff when entering orders or processing payments can lead to incorrect orders being delivered.
  Supply Chain Issues: Shortages of ingredients or disruptions in delivery can affect order fulfillment and timely service.
  Insufficient Training: Lack of training for employees on using the order system effectively can lead to operational inefficiencies.
  Poor Communication: Ineffective communication between front-of-house and kitchen staff can result in order mix-ups.
  Outdated Process: Failing to regularly update operational procedures based on feedback or issues can lead to repeated failures and inefficiencies.

Q4: Identify human mistakes, system faults, system errors, and system failures for the system
  1. Human Mistakes
  Incorrect Order Entry: Staff may enter the wrong items or quantities when taking orders.
  Miscommunication: Clear instructions may not be relayed from front-of-house to kitchen staff, leading to incorrect meals being prepared.
  Failure to Update Inventory: Staff might forget to log items used, resulting in overselling or confusion about availability.
  Inadequate Training: Employees may not be familiar with the system or menu, leading to mistakes in order taking or processing.
  Ignoring Customer Preferences: Staff may overlook special requests or dietary restrictions when entering orders.
  2. System Faults
  Application Glitches: The software might experience intermittent issues that affect usability but do not result in complete failure.
  Load Handling Problems: The system might slow down during peak hours due to unexpected high traffic, causing delays but not crashing entirely.
  User Interface Confusion: Poorly designed interface features can confuse users, leading to mistakes in order submissions or navigation.
  Communication Issues: Problems with how different system components (like POS and kitchen display systems) communicate can lead to incorrect transmissions of orders.
  3. System Errors
  Data Validation Errors: The system might allow invalid data entries (like negative quantities), leading to processing issues.
  Transaction Failures: Orders may fail to process due to payment gateway issues, resulting in incomplete transactions.
  File Corruption: Corrupted files in the system could prevent proper functionality, such as menu updates.
  Server Response Errors: The system may occasionally fail to respond appropriately to user actions due to bugs in the code, leading to confusion.
  4. System Failures
  Complete System Outage: The entire food order system may become unavailable due to server crashes or network failures.
  Database Failures: A database crash might lead to all order data becoming inaccessible, resulting in loss of historical information and current orders.
  POS Failure: The point-of-sale system might fail entirely, preventing any orders from being taken or payments processed.
  Integration Failures: Failure of third-party services (e.g., payment processors or delivery partners) might halt the entire order process.
  Inability to Process Orders: The system may not accept new orders due to a critical failure, halting operations.
