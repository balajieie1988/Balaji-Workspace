# Component Diagram
>Component diagrams are representative of a set of **`components`** and their relationships. The components present in these types of diagrams consist of classes, interfaces or collaborations. So such diagrams offer the **`implementation view`** of the system. During the design phase, software artifacts of the system are placed in various groups based on their relationship to each other. These groups are called components and are basically used to visualize the implementation process.
The components can be a software component such as a **database or
user interface; or a hardware component such as a circuit, microchip or
device; or a business unit such as supplier, payroll or shipping**.

## Component Diagram Symbols

### Component
#### There are three ways the component symbol can be used.

![Component](https://github.com/venu-shastri/ooad-uml-knowledge/blob/master/images/component-diagram-1.JPG)

### Provided Interface and the Required Interface
Interfaces in component diagrams show how components are **`wired `** together and **`interact`** with each other. The assembly connector allows linking the component’s **`required interface`** (represented with a  semi-circle and a solid line)with the **`provided interface`** (represented with a circle and solid line) of another component. This shows that one component is providing the service that the other is requiring

![interface](https://github.com/venu-shastri/ooad-uml-knowledge/blob/master/images/component-diagram-2.JPG)

### Port
Port (represented by the small square at the end of a required interface or
provided interface) is used when the component delegates the interfaces to
an internal class.

![port](https://github.com/venu-shastri/ooad-uml-knowledge/blob/master/images/component-diagram-3.PNG)

### Dependencies
The relationship between two components can be sown  using the ball-and-socket notation (provided interface and required interface), or ca be shown using   a dependency arrow to show the relationship between two components

![Dependency](https://github.com/venu-shastri/ooad-uml-knowledge/blob/master/images/component-diagram-4.PNG)


### Examples

#### Online Shopping Example
![OnlineShopping ](https://github.com/venu-shastri/ooad-uml-knowledge/blob/master/images/component-diagram-example1.PNG)
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzg5NDA5MDg4LC02NjI0MzMxMjgsMzU3OT
cxMjkzLC0xNjA0OTk5NDE5XX0=
-->