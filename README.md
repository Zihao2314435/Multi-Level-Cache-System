# Multi-Level Cache System

A three-level cache system implemented in Python using object-oriented programming and doubly linked lists.

## Overview

This project implements a cache hierarchy consisting of L1, L2, and L3 cache levels. It supports content insertion, retrieval, updates, and eviction while tracking cache capacity and available space.

A custom hashing mechanism based on content headers determines the appropriate cache level for each item. Each cache list uses a doubly linked list to organize stored content and support different eviction policies.

## Features

- Three-level cache hierarchy (L1, L2, and L3)
- Doubly linked list-based cache storage
- Content insertion and retrieval
- Content updates
- LRU (Least Recently Used) eviction
- MRU (Most Recently Used) eviction
- Cache clearing
- Capacity and remaining-space tracking
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

The system is organized into four main components:

- **`Node`** - Represents an individual node in a doubly linked list, with links to the next and previous nodes.
- **`ContentItem`** - Stores content ID, size, header, and content data, with custom hashing and equality behavior.
- **`CacheList`** - Manages linked-list storage, capacity, insertion, updates, and LRU/MRU eviction.
- **`Cache`** - Manages the three-level cache hierarchy and routes content to the appropriate cache level.

## Academic Context

This project was completed as part of Penn State's CMPSC 132 coursework.
