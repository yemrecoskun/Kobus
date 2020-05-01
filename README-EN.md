# Kobus (Kocaeli Bus))
## Programs,Languages Used In Our Project:
- ASP.NET MVC (HTML, CSS ,JS, C#)
- Linked List Of Data Structures (Bidirectional) Structure
- File operations (database))
- Layered Architecture
## The Purpose Of Our Project:
Ticket sales automation to a new bus company.
The Program consists of two parts: flight operations and ticket operations.
### Expeditionary Operations:
- The addition of all round and round trips is programmed manually.
- A bus entered in flight number, route information, date and time, passenger capacity, license plate, captain, ticket price has now been added to the itinerary list.
- All seats of a bus added to the flight list are numbered, passenger information, status (empty, booked, full), price, and features are automatically added to the list and made available.
- Adding the expedition, deleting the expedition, changing the captain, calculating the revenue of the expedition, listing the expedition, listing the past voyages, all the operations of the number of voyages should be done in the operations section.
### Ticket sales operations:
- This section should list the current voyages, the voyages should be selected.
- Information about the selected flight and bus seat information should be listed.
- Passenger information can be entered into an empty cargo,reservation and or sales can be made. The sale should be cancelled.
## The Software Architecture Of Our Project:
- The project is carried out in the form of a bi-directional linked list. [CiftYonluListe.cs](https://github.com/yemrecoskun/Kobus/blob/master/Kobus/Substructure/DoubleDirectionalList.cs)
- All recording operations are done to the text file.
- Daily operations [log()](https://github.com/yemrecoskun/Kobus/blob/master/Kobus/Entity/Entity.cs) function [log.txt](https://github.com/yemrecoskun/Kobus/blob/master/Kobus/File/log.txt file gg.AC.yyyy hh: DD-the operation is written as follows.
- Our project is completely dynamic.
