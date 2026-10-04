# Multi-Level Cache System

A three-level cache system implemented in Python using object-oriented programming and doubly linked lists.

## Overview

This project implements a multi-level cache system consisting of L1, L2, and L3 cache levels. Each cache level uses a doubly linked list to manage stored content and supports cache insertion, retrieval, updating, and eviction.

Content is assigned to a cache level using a custom hashing mechanism based on the content header.

## Features

- Three-level cache hierarchy (L1, L2, L3)
- Doubly linked list-based cache storage
- Content insertion and retrieval
- Content updates
- LRU (Least Recently Used) eviction
- MRU (Most Recently Used) eviction
- Cache clearing
- Capacity and remaining-space management
- Custom hashing and equality behavior
- Doctest-based testing

## Technologies

- Python
- Object-Oriented Programming
- Doubly Linked Lists
- Hashing
- Data Structures
- Doctest

## Implementation

The system is organized into three main components:

- **Node** — represents individual nodes in the doubly linked list.
- **ContentItem** — stores content ID, size, header, and content data and implements custom equality and hashing.
- **CacheList** — manages the linked-list structure, capacity, insertion, updates, and LRU/MRU eviction.
- **Cache** — manages the three-level cache hierarchy and routes content to the appropriate cache level.

## Academic Context

This project was completed as part of Penn State's CMPSC 132 coursework.
