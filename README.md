# Cogsworth React Code Challenge

## The challenge

We would like you to add a **Working Hours** component to this base application.

## What we are looking for

- You should spend no longer than *one hour* doing the challenge: we care less about finishing the whole challenge and more about explaining your approach
- Record yourself doing the challenge. Explain your thought process as you go
- Simplicity - avoid over engineering things, we write things for humans

## Component specifications

This component allows users to set their working hours.

It consists of seven horizontal bars (one for each week day) representing the 24 hours of the day. A draggable inner bar represents the day's working hours.

![working-hours](https://user-images.githubusercontent.com/871317/169369786-4df3ddd8-b681-4cb7-8e7c-fbd12e0f9b5c.png)

**Required functionality:**
  * Drag and drop the inner bar to change a day's working hours
  * Drag and drop from the inner bar's handles 
  * Click the trash can icon to remove a day's working hours
  * If a day has no working hours, clicking anywhere on it will add the default 09:00-17:00 working hours to it.
  * Props should take an `onChange: (value: WorkingHours) => void` callback that should be called every time the component working hours are updated.
  * Suggested interface for working hours value:
  ```
  interface WorkingHours {
    [day: string]: [number, number] // [900, 1730] => 09:00 to 17:30
  }
  ```

**Example**

https://user-images.githubusercontent.com/871317/169370758-789a5b5e-5bb6-476e-8c6c-70215a5b2494.mov



## Getting started

A few things you should be familiar with before jumping into the challenge.

### Stack

- typescript
- react
- scss
- [react-rnd](https://github.com/bokuweb/react-rnd)

### Prerequisites

Before you get started, ensure you've setup the following:

1. Checkout the code locally: https://github.com/cogsworth4/code-challenge
2. Install all dependencies: `yarn install`
3. Run the application: `yarn dev`
