URL Shortener System Design

Requirements

Generate short URLs
Redirect to original URLs
Handle millions of requests

Architecture

Client
  ↓
Load Balancer
  ↓
URL Service
  ↓
Redis Cache
  ↓
Database
