# Freight Tools

This repository contains a collection of tools designed to streamline various aspects of freight management. These tools are primarily developed in Python and focus on areas such as carrier tracking, email communication, cost estimation, and shipment time estimation.

## Carrier Tracking

The `carrier_tracking.py` script provides a way to manage information about carriers, including contact details, equipment types, service areas, and insurance coverage. It uses a MySQL database to store and manage the data.

## Email Communication

The `email_communication.py` script enables automated email communication with carriers or clients. It uses the `smtplib` library to send emails with customizable templates and can embed images such as logos.

## Freight Cost Calculator

The `freight_cost_calculator.py` script calculates the estimated cost of freight shipments based on distance, weight, volume, and other factors. It takes into account fuel costs, insurance, storage fees, and desired profit margins.

## Shipment Time Estimator

The `shipment_time_estimator.py` script estimates the total time required for a shipment, considering loading and unloading times, travel time, and regulatory constraints on driving hours. It uses the Google Maps API to estimate travel time and adjusts for breaks and daily driving limits.
