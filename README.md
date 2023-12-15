# Hall Booking API
## Technologies Used
  - NodeJS
  - Express
  - MongoDB

## Overview
 - Hall Booking API used to manage all the task realated to Hall Booking

## API Documentation

 - [Click Here](https://documenter.getpostman.com/view/31335509/2s9YeLXUS4)

## Endpoints
  Base URL - https://hall-booking-q9ll.onrender.com/

## POST Request 
    1.Adding a new Room
        - /room/add
        - If the Room ID already exist it will throw an Error

    2.Adding new Booking
        - /customer/add
        - If the Room ID already Booked for that date and time it will throw an Error

## GET Request
    1.Get All the rooms details
        - /room/all

    2.Get room details with customer who booked the room
        - /room/allroom

    3.Get Customer details
        - /customer/all

    4.Get Customer details with number of times they booked a room and room details
        - /customer/cus/count



