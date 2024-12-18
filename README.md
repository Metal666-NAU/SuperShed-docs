# SuperShed

This project is a prototype of a warehouse management system. I designed and developed it as one of my independent research assignments.

The following technologies where used during its development:

- [.NET 8](https://dotnet.microsoft.com/en-us/)
- [Godot Game Engine](https://godotengine.org/)
- [Flutter](https://flutter.dev/)
- [MongoDB](https://www.mongodb.com/)

SuperShed features the use of WebSockets, QR Code creation and scanning, 3D graphics (creation and manipulation of 3D objects and scenes), state management in Flutter using BLoC, and working with a MongoDB database.

The project consists of three separate pieces of software:

- [Admin](https://github.com/Metal666-NAU/SuperShedAdmin)  
  The Admin app lets users (managers) view a 3D representation of the warehouse, the list of available products and Server logs. It allows editing the location, size and other properties of racks inside the warehouse and can also be used to manage employee access. Additionally, QR codes for each product can be viewed; in a complete system, they would be automatically printed and attached to products, allowing the workers to scan them.

- [Worker](https://github.com/Metal666-NAU/supershed_worker)  
  Worker is an Android app for warehouse workers. Allows scanning products and editing their information.

- [Server](https://github.com/Metal666-NAU/SuperShedServerV2)  
  The Server enables communication between Admin and Worker clients + performs their authentication, reads and writes data to the Database.

A MongoDB database is used for data storage. All of the initial data needs to be entered manually, as the logistics, accounting and other subsystems are out of the scope of this project. The database schema looks like this:

![schema](https://github.com/user-attachments/assets/ebe298d7-2401-4a0c-aa0f-3ba09570b31d)

## Demo

https://github.com/user-attachments/assets/3575ee7a-acc7-441c-8f62-fb2fd1bbd166
