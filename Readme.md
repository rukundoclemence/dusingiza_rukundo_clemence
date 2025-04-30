## Project Overview

 This repository contains three systems implemented in java for the only purposeof OOP Assignment:
 **1. Motor Insurance System:** Manages insurance, claims, and vehicles.
 **2. Online Shopping System:** Handles shopping items, carts, and payments.
 **3. Stock Management System:** Tracs inventory, suppliers, and warehouses.

## Prerequisites

 **Java Development Kit (JDK) 11 or later
 ** Docker installed on your system

## Setup Instructins

### Running the Project with Docker

 **Option 1: Build and Run Locally**
 **1. Build the Docker Image:
       docker buid -t 26621-dusinginza-rukundo-clemence
 ** 2. Run the Docker Container: **
       docker run -it 26621-dusinginza-rukundo-clemence
**  3. Navigate and Execute: ** Inside the container, navigate to the desired system folder and compile/run the Java files. For example:

cd motor-insurance-system
javac Main.java
java Main

**Option 2: Use Docker Registry**
**1. Pull the Prebuilt Docker Image:
   docker pull rukundoclemence/26621-dusinginza-rukundo-clemence
** 2. Run the Docker Container:
   docker run -it 26621-dusinginza-rukundo-clemence
** 3. Navigate and Execute: Inside the container, navigate to the desired system folder and compile/run the Java files. For example:

cd motor-insurance-system
javac Main.java
java Main

## Running Locally

**1. Clone the repository:**
git clone https: //github.com

** 2. Navigate to the desired system folder and compile/run the Java files. For example:

cd motor-insurance-system
javac Main.java
java Main

## Project Structure

Dockerfile
Makefile
readme.md

motor-insurance-system/
         Claim.java
         collisionPolicy.java
         ComprehensivePolicy.java
         InsurancePolicy.java
         LiabilityPolicy.java
         Main.java
         Person.java
         RoadsideAssistancePolicy.java
         ThirdPartyPolicy.java
         Vehicle.java

Online-shopping-system/
        AccessoriesItem.java
        BooksItem.java
        ClothingItem.java
        Customer.java
        ElectronicsItem.java
        GroceriesItem.java
        Main.java
        Payment.java
        ShoppingCart.java
        ShoppingItem.java

Stock-management/
        ClothingItem.java
        ElectronicsItem.java
        FurnitureItem.java
        GroceryItem.java
        Main.java
        PerishableItem.java
        Product.java
        StockItem.java
        Supplier.java
        Warehouse.java

## License

This project is licensed under the MIT License.
