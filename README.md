
🧠 Low Level Design Projects – Java
This repository contains two Low-Level Design (LLD) projects implemented in Java with a strong focus on clean architecture, object-oriented principles, and extensibility.

♟️ 1️⃣ Chess Game – Console Based
📌 Overview
A console-based Chess Game built using proper class modeling and modular design.
The goal of this project is to demonstrate strong LLD thinking, separation of concerns, and extensible architecture.

🚀 Features
8x8 Chess Board implementation

Two-player support

Turn-based move validation

Custom Exception handling (InvalidMoveException)

Enum-based color management

Clean and modular class structure

🏗️ Design Architecture
Core Classes
ChessGame → Main game controller

Board → Maintains 8x8 grid of Cell objects

Cell → Represents each board position

Move → Encapsulates move details

Player → Stores player information

Color → Enum representing piece color

InvalidMoveException → Custom exception for invalid moves

ChessGameDemo → Entry point of application

🧠 OOP Concepts Used
Encapsulation

Abstraction

Custom Exception Handling

Enum Usage

Single Responsibility Principle

Clean modular architecture

▶️ How to Run
Compile:

Code

javac *.java
Run:

Code

java ChessGameDemo
🔮 Future Improvements
Add all chess pieces with individual movement logic

Check & Checkmate detection

Castling and En Passant

GUI integration (JavaFX / Swing)

Multiplayer support

🏷️ 2️⃣ Online Auction System
📌 Overview
A simplified Online Auction System designed using clean object-oriented principles.

The project models real-world auction behavior including:

User registration

Item listing

Bidding mechanism

Winner determination

🚀 Features
User management

Auction item creation

Bid placement

Highest bid tracking

Winner calculation logic

Clear separation between entities and service logic

🏗️ Design Approach
Core Entities
User

AuctionItem

Bid

AuctionService / Manager

Main (Entry point)

The system is designed to be easily extendable and scalable.

🧠 OOP Concepts Used
Encapsulation

Abstraction

Composition

Domain Modeling

Service Layer Design

Separation of Responsibilities

▶️ How to Run
Compile:

Code

javac *.java
Run:

Code

java Main
🎯 What This Repository Demonstrates
Strong fundamentals of Low-Level Design

Real-world system modeling

Clean class responsibilities

Scalable and extensible architecture

Interview-ready design thinking

📈 Planned Enhancements
Database integration

REST APIs using Spring Boot

Concurrency handling for bids

Time-based auction auto-closing

Unit testing (JUnit)

UML diagrams

👨‍💻 Author
Bibhanshu
B.Tech CSE (AI & ML)
Focused on DSA, LLD, and scalable backend systems.
