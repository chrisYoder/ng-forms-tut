# Reactive Forms Tutorial

## Reactive Forms 
- provide a model driven approach to handling forms inputs whose values change over time
- In this tutorial we will: 
  - create and update a simple form control
  - progress to using multiple controls in a group
  - validate form values
  - implement more advanced forms
  
## Introduction to Reactive Forms
- Reactive Forms use an explicit and immutable approach to managing the state of a form at a given point in time
- Built around observable streams
- provide predictability with synchronous access to the data model
- immutability with observable operators, and change tracking through streams

## Getting Started
- Import { ReactiveFormsModule } from '@angular/forms'

### Generate and Importing a New Form Control
- FormControl class is the basic building block when using reactive forms
- Import FormControl from '@angular/forms'
  - grants access to listen for, update, and validate the state of the form inputs
  
### Registering the Control in the Template
- you can bind a field using one way data binding

## Managing Control Values
- reactive forms give you access to the form control state and value at a point in time. You can manipulate the current state and value through the component class or template

### Displaying a Form Control Value
- You can display the value in these ways
  - Through the valueChanges observable where you can listen for changes in the form's value in the template using AsyncPipe or in the component class using the subscribe method
  - with the value property which gives you a snapshot of the current value
  
### Replacing a form control value
- Reactive forms have methods to change a control's value programatically 
  - gives us the ability to update the value without user interaction
  - setValue( 0method)

## Grouping Form Controls

  
  