# Problem Statement

### Adapter-Pattern

Plugging Devices into Power Outlets

You are developing an application that helps users manage and control various electronic devices by plugging them into power outlets. Each device has different plug types, voltage, and amperage requirements. To ensure compatibility and safety, you need to create adapters for different devices to allow them to be plugged into standard power outlets.

Adaptee Objects:

Laptop - Represents a laptop device that needs to be plugged into a power source. It has the charge() method.

Refrigerator - Represents a refrigerator device that requires a power source. It has the startCooling() method.

SmartphoneCharger - Represents a smartphone charger that needs to be plugged in for charging. It has the chargePhone() method.

Target Object:

PowerOutlet - Represents a standard power outlet with a common interface for plugging in devices. It defines the plugIn() method as the target method.

Adapter Objects:

LaptopAdapter - An adapter for plugging a laptop into a standard power outlet. It adapts the Laptop to the PowerOutlet interface, translating plugIn() to charge().

RefrigeratorAdapter - An adapter for plugging a refrigerator into a standard power outlet. It adapts the Refrigerator to the PowerOutlet interface, translating plugIn() to startCooling().

SmartphoneAdapter - An adapter for plugging a smartphone charger into a standard power outlet. It adapts the SmartphoneCharger to the PowerOutlet interface, translating plugIn() to chargePhone().

Here is the link to my UML Class Diagram:

https://lucid.app/lucidchart/4f41e07d-ede8-4122-bf79-46228f987110/edit?view_items=DGnFD07qU3j.&invitationId=inv_211917bd-e124-436c-8e3d-e8d5d4babbdc
