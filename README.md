# Multi-Level Cache System

A three-level cache system implemented in Python using object-oriented programming and doubly linked lists.

## Overview

This project implements cache operations across three levels (L1, L2, and L3), using object-oriented programming and doubly linked lists. The assignment provided the overall class structure, and I implemented the designated methods marked `YOUR CODE STARTS HERE`.

My contributions focused on implementing cache operations, managing linked-list pointers, tracking capacity, and handling cache insertion, retrieval, updates, and eviction.

## Features Implemented

- Custom hashing based on content headers to determine cache placement
- Doubly linked list operations for cache storage
- Content insertion with capacity and duplicate checks
- Cache retrieval and movement of accessed items to the front
- Content updates with capacity validation
- LRU (Least Recently Used) and MRU (Most Recently Used) eviction
- Cache clearing and capacity tracking
- Cache hierarchy operations for insertion, retrieval, and updates

## Technologies and Concepts

- Python
- Object-Oriented Programming
- Doubly Linked Lists
- Hashing and Equality
- Data Structures
- Cache Management
- LRU and MRU Replacement Policies

## Implementation

The assignment provided the class framework for `Node`, `ContentItem`, `CacheList`, and `Cache`. I implemented the designated methods within these classes, including:

- **`ContentItem.__hash__`** — Calculates a hash value from the content header.
- **`CacheList.put`** — Handles insertion, duplicate detection, capacity checks, and eviction.
- **`CacheList.__contains__`** — Searches for content by ID and moves accessed items to the front.
- **`CacheList.update`** — Updates stored content while maintaining capacity and list order.
- **`CacheList.mruEvict` and `CacheList.lruEvict`** — Remove the most recently or least recently used item.
- **`CacheList.clear`** — Resets the list and its capacity tracking.
- **`Cache.insert`, `Cache.__getitem__`, and `Cache.__setitem__`** — Implement cache-level selection and hierarchy operations.

## Academic Context

This project was completed as part of Penn State's CMPSC 132 coursework.
