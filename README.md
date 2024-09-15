# PRODIGY_SD_03

Simple Contact Management System --->>

Develop a program that allows users to store and manage contact information. The program should provide options to add a new contact by entering their name, phone number, and email address. It should also allow users to view their contact list, edit existing contacts, and delete contacts if needed. The program should store the contacts in memory or in a file for persistent storage.

explanation ---->>> Struct Definition: The Contact struct defines the structure of a contact with name, phone, and email fields.

Global Variables:

contacts: An array to store contact information. contactCount: A counter to keep track of the number of contacts. Functions:

loadContacts(): Reads contacts from a file and populates the contacts array. saveContacts(): Saves the current contacts array to a file. addContact(): Adds a new contact to the contacts array and saves it to the file. viewContacts(): Displays the list of contacts. editContact(): Edits an existing contact based on user input. deleteContact(): Deletes a contact from the contacts array and updates the file. Main Function: The main() function provides a menu-driven interface to interact with the contact management system, allowing users to add, view, edit, and delete contacts.
